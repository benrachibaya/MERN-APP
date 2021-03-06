# MERN-APP
Creating a full-stack Login/authorization app using the MERN stack (MongoDB for the database, Express and Node for the backend and React for the Frontend)


## BACKEND
The app allow user to:
   * Register
   * Login
   * Access protected pages 
   * Stay logged in after closing the app or refreshing the page
   * Logout
  
### Step 1:
   * Install VS code or any editor you like
   * Install latest Version of Node.js (I used npm or "Node package Manager" to install dependencies)
   * Install MongoDB
   * Install PostMan
     
### Step 2:
   * initialise your project
   ``` bash
       mkdir  mern-auth    (create a directory)
       cd mern-auth        (change to the directory)
       npm init            
   ```
 (init your project -- this will walk you through the creation of the package.json file. you could accpet                                the defaults values initially; changing the "index.js" to "server.js")                                  
                                   
 Once completed, your folder will have the package.json file which you can open in VS.
     
### Step 3:
   * Install the following dependencies 
   ``` bash
    npm i bcryptjs body-parser  concurrently  express is-empty jsonwebtoken mongoose passport passport-jwt validator
   ```
        
The installed packages:
   * [body-parser](https://www.npmjs.com/package/body-parser): will be used to parse incoming request bodies in the middleware
   * [bcryptjs](https://www.npmjs.com/package/bcrypt): will be used to hash inputted passwords before storing these in the database
   * [concurrently](https://www.npmjs.com/package/concurrently): will allow us to run the backend and the frontend concurrently on different ports
   * [express](https://www.npmjs.com/package/express): sits on top of Node to make the routing, request handling and responding easier to code
   * [is-empty](https://www.npmjs.com/package/is-empty): handy global function to use with validator
   * [jsonwebtoken](https://www.npmjs.com/package/jsonwebtoken): used for the authorization process
   *[mongoose](https://www.npmjs.com/package/mongoose): used to interact with our database MongoDB
   * [passport](https://www.npmjs.com/package/passport): used to authenticate requests, done through an extensible set of plugins known as strategies
   * [passwort-jwt](https://www.npmjs.com/package/passport-jwt):  passport strategy for authenticating using a JSON Web Token (JWT); It allow you to authenticate endpoints call using a JWT
   * [validator](https://www.npmjs.com/package/validator): will be used to validate user inputs 
       
### Step 4: Setting the database
   
### Step 5: Setting the server with Node.js and Express
   
### Step 6: Setting the database schema
   *  Configuration: make sure that you add your own MongoURI from your mLab database in the config/keys.js file
   
### Step 7: Setting the form validation
   
### Step 8: Setting up the API routes
   
### Step 9: Testing the API routes with Postman
       
       
## FRONT-END      

      
     
