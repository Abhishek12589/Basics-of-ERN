# Basics-of-ERN

# Initializing fILE

Every software will behave like a server if it have the ability to handle the http request, for import in nodejs we use require 
keyword'

var http = require("http")

res.end == will read only string parameter,
We will read file in nodejs using fs(fileSystem)

filesystem will read the html type of data and with utf-8 encoding we can convert this in string format, it will give two paremeter (err, data) and git the response on the browser.

# Express

From here on we will learn about Express.js It is built on top of node.js Express is mainly used for routing and middleWare, it is highly beneficial..

# Below is the basic code of Express

var express = require("express")
var fs = require("fs")
var app = express()

app.get("/", function(req,res){
    res.end("hello world")
})

app.listen(3000, function(){
    console.log("Server is Listening on 3000")
})

