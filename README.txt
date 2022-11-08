# node-express
Detail explanations


mkdir projectname
cd into that folder 
then install express into that folder using following command
npm install express
to run the program just type node app.js

then create 2 files 
app.js
index.html

app.js :
const express = require('express')
const app = express()
app.get('/', function(req, res){
    res.sendFile(__dirname+"/index.html")
})
app.listen(3000, function(){
    console.log('Server is started on port 3000');
})

index.html file:
normal html code
