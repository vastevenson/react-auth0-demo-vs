### React auth0 Example App

### Background 
This react app uses auth0 to host oauth authN flows and lets users use their Google Account to authN to the site. This was created following the documentation here: https://auth0.com/docs/quickstart/spa/react

To run this service, run cmd: `npm start` - it should be running at localhost:3000

Note that if this service is running on different hosts, we need to add those hosts to the Application URIs section - else the authN flow will fail. Currently, only http://localhost:3000 is under these URI lists. 

