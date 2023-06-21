# Authentication-Security

Six level of Authentication 

1. Username and Password;
2. Encryption
3. Hashing
4. Salting and Hashing with bcrypt
5. Passportjs to add cookie and Session
6. Third party authentication with google Oauth

## How To Run

First clone this repo and create a `.env` file at root route and it must contains keys :

- SECRET = write somthing secret here
- DB_URL = mongodb url
- CLIENT_ID = google client id
- CLIENT_SECRET = google client secret

After creating `.env` now we are ready to run the project

```bash
npm install
node app.js
```

Now visit http://localhost:3000 and we can access the website. 


