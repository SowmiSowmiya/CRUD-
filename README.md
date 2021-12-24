
# crud application using nodejs and express js     

Table of Contents


1.Create Project and Install Dependencies     
2.Create Database, Table and Connect to Database  
3.Make CRUD Routes    
4.Create View Files  
5.Import Created Files to app.js





## Deployment

To deploy this project run

# with NPM command
npm install -g express-generator

# create project
express --view=ejs nodejs-crud

# go to the project folder:
cd nodejs-crud

# to send flash message:
npm install express-flash --save
# to make session like PHP:
npm install express-session --save
# to send PUT and DELETE requests:
npm install method-override --save
# driver to connect Node.js with MySQL:
npm install mysql --save

# run project:
npm start

# project URL:
http://localhost:3000

# books crud URL:
http://localhost:3000/books
