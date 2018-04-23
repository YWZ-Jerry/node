# No Sql
https://github.com/YWZ-Jerry/node.git
1.config ENV 
set mongodb program work path
***
2.config db 
mongod --dbpath d:\mongodb\db
***
3.add config file 
\mongodb\mongod.cfg
***
systemLog:
    destination: file
    path: d:\mongodb\log\mongod.log
storage:
    dbPath: d:\mongodb\db
***
4.test 
    1) run server side use mongod
    2) run client side use mongo

***
### create db 
1.command  use DATABASE_NAME
    i.e : use jddb
    switch to jddb
2.insert one data
    db.jddb.insert({"name":"hello world"})
3.show dbs
4. delete db 
    db.dropDatabase()
5.




