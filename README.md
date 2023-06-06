
Start:

Please run npm init to add the node_modules directory

Info:

This project connects to a mongodb collection of documents that is stored locally on my computer. Make sure you have a mongodb account with the correct uri entered into db.js. A json file is added to project for a template but feel free to use whatever data you like. Run the server through the terminal with node and type http://localhost:3000/books into your browser to view all the books in your database.

To fetch a specific document type http://localhost:3000/books/{ObjectId} into the browser to retrieve that specific book.

Post, Patch and Delete request only have functionality through an api platform like Postman which is what I used to have the functionality. 

Post:
Download Postman, change the request to Post, type http://localhost:3000/books, click on body->raw->JSON, then add the json information you want.

Patch:
Download Postman, change the request to Post, type http://localhost:3000/books/{ObjectId}, click on body->raw->JSON, then add the json information you want to update for that document.

Delete:
Download Postman, change the request to Post, type http://localhost:3000/books/{ObjectId} to delete that document.