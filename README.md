# What to consider when starting your project.

## General setup

1. Make a folder which will be the root of you projet -> mkdir nameOfProject.
2. Go into folder -> cd nameOfProject.
3. create a react application called client -> npx create-react-app client
4. create an express application called server -> express server (we do not need to set a view engine, because we use react).
5. Get necessary dependencies.
   - For the server that will be at least -> npm i mongoose express-session connect-mongo cors dotenv
   - The client that will be at least: npm i react-router-dom axios
6. Set the configuration.
   - in the server that'll be a .env file in the root. With at least the MONGO_URI=location-of-your-db.
   - change the port on where the server is listening on to 3001 (in the server/bin/www), to anythying other than port 3000 (your react app).
   - in the client create a .env.development file. With the environment variable = REACT_APP_BASE_URL=http://localhost:3001/api/

## Getting the backend ready.

1. Make a connection to your database.
2. set session and store session in mongo store.
3. set the cors.
4. create your first data models.
5. make api endpoints that will allow basic CRUD operations.
6. test crud operations with postman.

## Getting the front end ready.

1. Start with appropriate folder structure:

```
/src
    /api
    /components
    /pages
    /styles
```

2. Configure react-router-dom as high as possible in your app. Ideally index.js.

## Version control setup (github) IMPORTANT JAMESSSS

1. remove the .git folder from the client, and move .gitignore to the root folder of your project.
2. create remote repository on github,
3. follow steps provided by github.
4. commit your code.
5. commit your code.
6. commit your code.
7. commit your code.
8. commit your code.
9. commit your code.
10. James, commit your code.
