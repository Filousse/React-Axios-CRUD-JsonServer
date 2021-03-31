# React-Axios-CRUD-JsonServer
Basic react CRUD template using JsonServer : 

=====================================
For me :
Init Json Server and app with command Line :

cd server-api
npm start

cd App-CRUD-Axios-JsonSever
npm start

======================================
for the others:
Init personal JsonServer :

1 in the same place of the root projet :
create: api-server

2 commande line : 
cd server-api
npm init --yes

3 create api-server/db.json (and your json exempe)
[
    {
    id: "0",
    name: "Tibo",
    email: "tibo@gmail.com"
    },
    {
    id: "1",
    name: "Lucas",
    email: "lucas@gmail.com"
    },
    {
    id: "6ddff8e4-a34a-44f0-b39b-948054a2a343",
    name: "Paula",
    email: "paula@gmail.com"
    }
]

4 make a script in server-api/package.json :
  "scripts": {
    "start":"json-server -p 3006 -w db.json"
  },
  
5 starting server JsonServer :
  On comande line : 
  cd server-api
  npm start
  
  
 HAPPY HACKING with jsonServer Backend !!!!


