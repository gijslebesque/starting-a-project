# What to consider when starting your project.

## General setup

1. Make a folder with a react client and an express backend.
2. Get necessary dependencies.
   - For the server that will be at least: npm i mongoose express-session connect-mongo cors dotenv.
   - The client that will be at least: npm i react-router-dom axios.
3. Set the configuration.
   - in the server that'll be a .env file in the root. With at least the MONGO_URI=location-of-your-db.
   - change the port on where the server is listening on, to anythying an other port then 3000 (or your react app).
   - in the client create a .env.development file. With the environment variable = REACT_APP_BASE_URL=location-of-your-express-app.

## Getting the backend ready.

1. Make a connection to your database.
2. set session and store session in mongo store.
3. set the cors.
4. create your first datamodels.
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
