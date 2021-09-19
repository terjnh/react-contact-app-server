# Notice
This provides a 'mock' server-api for contact-app project


# Instructions

1. Install package.json file
   $ npm init --yes

2. Install the json server
   $ npm i --save json-server

3. Create db.json file

4. Change "script" in package.json
   "scripts": {
   "start":"json-server -p 3006 -w db.json"
   },

5. Start json server
   In our case, it will start at port 3006 based on package.json

6. Install Axios (in contact-app)
   $ npm i --save axios

# REST API

Actions | HTTP Method | Endpoints
Get all contacts | GET | /contacts
Create contact | POST | /contacts
Update contact | PUT | /contacts/:id
Delete contact | DELETE | /contacts/:id
