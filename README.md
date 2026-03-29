## Postman Api Automation Integration with Github Action ##

This repository is a demonstration POC for integrating postman guthub actions . Thhe Tests are written in Postman and they aner executed on VM with the help of the newman and newman-reporter-htmlextra.
Github action will trigger the project execution on every push to the main branch. You can also execute the project manually using workflow_disatch.The Project runs on a schedule time with the help of cron job.

The HTML is archieved and kept in the artfact section for the team to download it . Along with that hey can view and report directly from github page :https://kalpeshkp1995.github.io/Phoenix-Inwarranty-Flow/
The latest report is mailed to the team members using GMAIL SMTP.

## 🚀 About Me
Hi My Name is Kalpesh Patil and I have 4 years of experience in Automation Testing using technologies like Selenium Webdriver , RestAssured , Playwright with Typescript , CI CD 

## Author
- [@Kalpeshkp1995](https://github.com/Kalpeshkp1995)
- EmailAddress: patilkalpeshkp95@gmail.com

## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://github.com/Kalpeshkp1995)

[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kalpeshkp1995/)

## Testing Coverage ##
1. Happy Flow Testing
2. Negative Testing and Edge Case Testing
3. Token Testing
4. Data Driven Testing with CSV
5. Schema Validation
6. Secreets Management with Github Secrets

## Tech Stack ##
1. Postman
2. Nodejs 22v
3. Newman
4. Newman-Reporter-Htmlextra
5. Github Actions
6. Gmail SMTP
7. Github Pages
8. CSV for Data Driven Testing
9. AWS-EC2 instance for self hosted github runner

## Github Pages ##
You can directly view the latest test report of the Postman Test at the Github Page Link: https://jatin99.github.io/Phoenix-Inwarranty-Flow/

## HTML Report ##
The Report will be created in the newman folder
![Postman Report](https://github.com/Kalpeshkp1995/Phoenix-Inwarranty-Flow/blob/static-content/Newman-Report.png)

## How to run the Project? ##
You can run the project on your local system for that:
1. Clone the Project on Local System: https://kalpeshkp1995.github.io/Phoenix-Inwarranty-Flow/
2. Install Nodejs and NPM from https://nodejs.org/en
3. Install Newman using npm install -g newman
4. Install Newman-reporter-htmlextra npm install -g newman-reporter-htmlextra
5. Run the Newman Command:
   
   newman run 'Inwarranty-flow Collection.postman_collection.json' \
   -e QA.postman_environment.json \
   -d testdata.csv \
   -r cli,htmlextra \
   --reporter-htmlextra-export ./newman/index.html



