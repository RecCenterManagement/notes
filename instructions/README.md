# Running the Project
Launching the RecCenter Management project in development mode is fairly straightforward thanks to the use of a well-established technological stack.


## Frontend 
The frontend project is implemented in React.js. To launch the frontend in the development server, navigate to the root directory and execute 
 
```$ npm install```

to install dependencies locally, followed by

```$ npm start```

The frontend populates it's data by making requests to REST endpoints on the targeted backend, as defined in `package.json`

## Backend
The backend is built on the JHipster framework and as such is in turn built on Spring Boot. The project build process is managed by Gradle. The project can be launched in development mode by navigating to the root directory and executing

```$ ./gradlew```

or 

```$ gradlew.bat``` 

on Windows

The embedded Tomcat server will listen for REST calls on `localhost:8080` by default. A development database console can be accessed by navigating to `/h2-console` in the web browser. 

By default the project supports logins `'admin'` with password `'admin'` and `'user'` with password `'user'`
