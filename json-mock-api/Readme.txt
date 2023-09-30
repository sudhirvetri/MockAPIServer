#1. Create a new folder json-mock-api
mkdir json-mock-api

#2. initialise the folder with node , to create a package.json file
npm init -y

#3. edit the package.json file, the code can be found in the package.json file

#4. install json-server and Casual libraries
npm install json-server casual --save-dev

create a new folde src and
src/db.json

Inside the db.json file paste your actual json Output that need to be displayed

to run the output in local host

 npx json-server --watch src/db.json

if url =https://reimagined-halibut-wrxvg494gwg2v9w6-3000.app.github.dev/
url/Employee
url/photos
both are get request that can be used as a mock server urls.

