# 001067923_Tarush_G_Singh Assignment 8
Design a mongoDB based application and implement create read update and delete functions. The application also uses Bcrypt to encrypt the password data.

# Steps to setup the app
 Use npm install to install the libraries mentioned in the package.json file
```
npm install
```

Use npm start inside of the directory *001067923_Tarush_G_Singh-Web-Design-and-user-experience-*
```
npm start
```

The node should connect to a mongoDB. If you have your own cluster or are running the files locally, edit *MONGO_URI* present inside the *config/config.env* to your own mongoDB URL. You can then use Postman to pass data as a json. The routes for the same are: \n

For POST:
```
http://localhost:3000/user/create
```

For GET:
```
http://localhost:3000/user/getAll
```

For UPDATE:
```
http://localhost:3000/user/edit/<The email ID whose data you want to change>
```

For DELETE:
```
http://localhost:3000/user/delete/<The email ID whose data you want to delete>
```

The schema for the data entry is as follow:
```
{
    "email": "xyz@northeastern.edu",
    "fullname": "xyzNoSpaces",
    "password": "password"
}
```