# dt-tools
Some simple scripts to access the API at Disruptive Technologies
All scripts are NodeJS

install dependencies with 
```
npm install
```
run scripts with
```
node "name-of-script"
```

##Prerequisities
Node must be installed

A file named 'apikey.ns' must be created and contain the Basic Authentication for communicating with the API and the id of the project

```
const DT_API_V2_PROJECT_ID = '"project-id"';
const DT_API_V2_AUTH_BASIC = 'Basic "key:secret Base64encoded"';
```
The autentication is with a ServiceAccount defined in DT Studio that must be allowed for "Basic Authentication".