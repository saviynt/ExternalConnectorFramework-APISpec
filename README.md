# ExternalConnectorFramework-APISpec

This is the repository for External Connector Framework Open API Spec

## Steps to generate client libraries
1.	Download Swagger Editor zip from https://github.com/swagger-api/swagger-editor
2.	Unzip the file and run index.html
3.	It will open an editor in your browser:
4.	In the editor, click on File --> Import file and select the OpenApiSpec.yaml from the spec directory of ExternalConnectorFramework-apispec project (ensure that you have already checked this out)
4.	You should be able to render the API specification on right panel as shown in above screenshot.
6.	Now go to Generate Server -> nodejs-server
7.	This will generate a zip file.
8.	Unzip this zip file. (This will be base location of your node js project)
9.	Install nodejs from https://nodejs.org/en/download.
10.	Once node js is installed, go to base location and run “npm start” command.



## Supported Objects
* Accounts
    - Import all accounts
    - Create an account
    - Add Role membership
* Entitlements
    - Role
        - Import all roles
        - Get Memberships