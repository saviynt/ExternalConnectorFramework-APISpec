# ExternalConnectorFramework-APISpec

This is the repository for External Connector Framework Open API Spec

## Steps to generate node-js server.
1.	Open Swagger Editor in web broswer by navigating to https://editor.swagger.io/
2.	In the editor window, click on File --> Import file and select the OpenApiSpec.yaml from the spec directory of ExternalConnectorFramework-apispec project (ensure that you have already checked this out)
3.	You should be able to render the API specification on right panel.
4.	Now go to Generate Server -> nodejs-server
5.	This will generate a zip file.

## Steps to start node-js server.
1.	Unzip the zip file. (This will be base location of your node js project)
2.	Install nodejs from https://nodejs.org/en/download.
3.	Once node js is installed, go to base location and run “npm start” command.
4.  You should be able to see below message.
        Your server is listening on port 8080 (http://localhost:8080)
        Swagger-ui is available on http://localhost:8080/docs
    
This will mean you have successfully started the node-js server.

## Steps to navigate the API spec.
1. Go to web browser and navigate to http://localhost:8080/docs.
2. This will list all API spec supported by External Connector Framework.
3. There are various operations listed, as per your requirement, you can go to that specific API and use "Try it out" option to explore the API specification, which will list request type, request parameters, body and response.

Note:
1. "Try it out" will require you to authorize with a bearer token, so you should first click on Authorize button at the top provide a value, this is a sample spec and there is no actual token validation, so you can provide any string value for e.g. MyBearerToken and click on Authorize -> Close.
   
## Supported Objects
* Users
    - Import all users
    - Update a user  
* Accounts
    - Import all accounts
    - Create an account
    - Update an account
    - Enable an account
    - Disable an account
    - Delete an account
    - Change account password
    - Add Group membership
    - Remove Group membership
    - Add Role membership
    - Remove Role membership
* Entitlements
    - Group
        - Import all groups
        - Import group-account association
    - Role
        - Import all roles
        - Import role-account association
        - Get Memberships
