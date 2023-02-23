# Holy Grail App 🎨

Here's the example

<img src = 'https://github.com/mkp9233/Holy_Grail_App/blob/main/public/example.png?token=ATDMTEDNTR4WVHJ53R25ZADBNPK5G' width="400" height="340"> 

## Tasks:

● Set up the Redis Docker container locally. 
● Install the Redis npm package. 
● Update the index.js file to include the following: 
○ "header", 0, "left", 0, "article", 0, "right", 0, "footer", 0 
○ Create a Redis client. 
○ Use the Redis client to initialize values for header, left, article, right, and footer. These values should be 
"header", 0, "left", 0, "article", 0, "right", 0, "footer", 0 
● Implement the data() method to use Promises to get the values for header, left, right, article and footer using the Redis client. 
● Implement the /update/:key/:value endpoint by using the Redis client to update a given key-value pair. You should first locate the records matching the provided key and then update it to the new provided value. 

## Installation

- Install Redis then run it with `src/redis-server`
- ```npm install```
- `node index.js` run on `http://localhost:3000`.

## Usage

<img src = 'https://github.com/mkp9233/Holy_Grail_App/blob/main/public/server.png?token=ATDMTEFBO4QJRPZRFW4K4WDBNPNYY' width="300" height="220"> 

<img src = 'https://github.com/mkp9233/Holy_Grail_App/blob/main/public/server1.png?token=ATDMTEFBO4QJRPZRFW4K4WDBNPNYY' width="300" height="220"> 

<img src = 'https://github.com/mkp9233/Holy_Grail_App/blob/main/public/example.gif?token=ATDMTEAYRRPT223GZJJKUTDBNPK5I' width="550" height="440"> 


 
