# Bare Bones User Registration

This is a bare bones user sign up and login page and uses mysql to manage user logins.

## Deployment Instructions
- First install all the required node modules

```
npm install 
```

- Make sure you have a database called HealthForm in mysql. Change the database.js in the config file to suit your local mysql configurations.
Run the db.sql with mysql to create the users table. with one entry.

For running development environment
``` 
npm run dev
```

To run the app
```
npm start
```

## TO DO
The app in it's current form doesn't function properly. The users tables isn't getting updated as expected and the sign up page doesn't load the profile page or update the table properly.