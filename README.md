CouchBase DB Notes:




http://127.0.0.1:5984/_utils/index.html


pragativyas$ curl -X GET http://localhost:5984

Pragatis-MacBook-Air:~ pragativyas$ curl -X GET http://localhost:5984/_all_dbs
["_replicator","_users","register","test_suite_db","test_suite_db2"]

Pragatis-MacBook-Air:~ pragativyas$ curl -X PUT http://localhost:5984/register
{"error":"file_exists","reason":"The database could not be created, the file already exists."}

Pragatis-MacBook-Air:~ pragativyas$ curl -X PUT http://localhost:5984/address
{"ok":true}



Pragatis-MacBook-Air:~ pragativyas$ git clone git@github.com:VyasPragati/prj01.git

Pragatis-MacBook-Air:~ pragativyas$ ssh-keygen -t rsa

Your public key has been saved in /Users/pragativyas/.ssh/id_rsa.pub.

Pragatis-MacBook-Air:~ pragativyas$ pbcopy < ~/.ssh/id_rsa.pub

Pragatis-MacBook-Air:~ pragativyas$ mv /Users/pragativyas/prj01 /Users/pragativyas/Documents
