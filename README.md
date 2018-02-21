# dt-tools
Some simple scripts to access the API at Disruptive Technologies
All scripts are NodeJS

install dependencies with 
```
npm install
```
run scripts with
```
node <script>
```

##Prerequisities
Node must be installed

A file named 'apikey.ns' must be created and contain the Basic Authentication for communicating with the API
```
const DT_API_V2_AUTH_BASIC = 'Basic <usr:pwd Base64encoded>';
```
The autentication is with a ServiceAccount in DT Studio.