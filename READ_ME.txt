node.js installed in "vue first" folder.

Local:   http://localhost:8080/
Network: http://192.168.0.200:8080/


to run surver/to create server
in cmd "npm run serve" (SERVE)




For JSON server
cmd command: 
npm install -g json-server

for Linux, try
sudo npm install -g json-server

to run/start JSON server:
*go to that JSON file through cmd & type

json-server --watch users.json

note: use indipendant cmd, not VS's cmd

Resources
http://localhost:3000/users

Home
http://localhost:3000




"serve": "vue-cli-service serve",
    "build": "vue-cli-service build",
    "lint": "vue-cli-service lint"
    
    
    "start": "json-server --watch users.json",
