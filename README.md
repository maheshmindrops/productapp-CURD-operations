# productapp-CURD-operations
Writing a CRUD app with Node.js and MongoDB

An API for a Products app.

Initialize npm init and export these packages.
npm install --save express body-parser mongoose

Database URL : mongodb://<dbuser>:<dbpassword>@ds031278.mlab.com:31278/productsapp
  User : someuser
  Pass : abcd1234
  
  
Postman : 
  GET : localhost:1234/products/test
  
  POST : localhost:1234/products/create
  //Enter key and value, pass these in body.
  
  GET : localhost:1234/products/5bbb3255c6cc0a17b82590b3
  //Get product details
  
  PUT : localhost:1234/products/5bbb3255c6cc0a17b82590b3/update
  //Update product of given ID.
  
  DELETE : localhost:1234/products/5bbb3eb369d93a1970079b11/delete
  // 5bbb3eb369d93a1970079b11 = Product ID
