# Dmoney API Automation
## Project summery: Performed Dmoney API testing using Postman. I have automated some CRUD Functionalities for user

## Tools I have used: 
1. Newman
2. Postman
3. nodejs

## How to run:
**1. Packege generate:** 'npm init -y'

**2. Newman package install:** 'npm i newman' 

**3. Clone this project:** Export Collection folder and save as collection.json formet then write 'npx newman run .\collection\collection.json'

**4. Install npm package:** 'npm i newman-reporter-htmlextra'

**5. Collection Link:** disable collection API or Documentation link and enable exported collection folder from report.js file at VS Code. 
collection: require('./collection/collection.json'),

**6. Disable this code:** 
require("dotenv").config()

**7. Generate newman report:** 'node .\report.js'

** Documentation for API:** [Check here](https://documenter.getpostman.com/view/40659331/2sAYJAfxmb)
** Test Cases:** 
** Bug reports:** 

## Output
![image](https://github.com/user-attachments/assets/0c10e3eb-f39d-4d05-b4c2-820f8e8df994)
