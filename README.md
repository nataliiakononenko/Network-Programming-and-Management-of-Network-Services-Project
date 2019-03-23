# Network-Programming-and-Management-of-Network-Services-Project
This is a school project for Network Programming and Management of Network Services class. 
Includes among other things a simple web-server written in c, an Apache server, a simple REST-api (Node.js and Express.js) in Docker containers, an Ajax client and a simple Android app.

C-server is demonized and sends HTTP-response with files of appropriate mime-types. It lies in a Scratch Docker-container.

Apache server lies in a httpd:alpine Docker container and includes a bin with cgi-scripts that send requests to the REST-api.

REST-api is built with Node.js and Express and returns queries from a connected database available depending on whether the user is logged in. 

An Ajax client gives the save functionality as the cgi-scripts.

The android app is just a simple HTML-page saved in the Assets catalog with a single link to a web-view of the ajax-client from the express-container.

Complete text of the assignment is in the Assignment file (Norwegian).
