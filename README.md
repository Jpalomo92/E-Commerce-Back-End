# E-Commerce-Back-End

  ## Badges
  [![Apache license](https://img.shields.io/badge/License-Apache-brightgreen.svg)](http://www.apache.org/licenses/LICENSE-2.0)

  ## Table of Contents
  * [License](#license)
  * [Description](#description)
  * [Installation](#installation)
  * [Usage](#usage)
  * [Contributing](#contributing)
  * [Tests](#tests)
  * [Questions?](#questions)


  ## Description
  This is a back end application that allows the user to view all products, categories, tags, and even make necessary updates on the respective products, categories, and tags. The application gives the user the ability to create a product, category, and/or tag, post it, and delete it. 
  
  Please see the Usage section as a guide on how to use the Employee Tracker application.


  ## Installation
  To install this application, please copy the ssh link from the repo, and paste it using git clone.

  ## Usage
  To use this application, be sure that you are in the correct file path in your command-line/terminal. 

  ### Sourcing The Databases
  1. Once you are in the correct file path of the cloned files, you will need to first source the databases. This will tell the application where to source the data from. To source the data, type 'mysql -u root -p'. You will be prompted to enter in a password.
  2. When the user has entered in their password, first source the schema database by typing 'source db/schema.sql' and hit enter.
  3. After sourcing the schema database, type 'quit' and hit enter. From here, you will need to source the seeds. 
  4. Type 'npm run seed' and hit enter. You will see in the terminal that all of the seeds have been synced.
  5. You are then brought back to the file path. 

  ### Running And Using The Application
  1. After sourcing the databases, you are now free to run the application. 
  2. Type 'npm start' in your command-line and hit enter.
  3. The application is now running and listening.
  4. Go to the Insomnia application.
  5. If the user is wanting to see all categories, products, or tags, the "GET" method will need to be used. The http path to enter in the address bar will be "http://localhost:3001/api/'route'" Be sure to replace 'route' with the data that you would like to see.
  6. If user only wants to see a certain category, the respective ID will need to be entered into the http path. EX: "http://localhost:3001/api/categories/1". This will also apply to both products and tags.
  7. If user wants to post for one of the directories, the "POST" method will need to be used. The user will need to be in the respective route. From here, the user will need to enter in the appropriate JSON information in the body. Once you have submitted you will receive a new ID number.
  8. To use the "PUT" method, then the user will be able to enter in the JSON information in the body and submit it to the new ID number created using the appropriate http path. 
  9. If the user will like to delete a certain item, use the "DELETE" method, go to the appropriate http path and ID number, and submit delete. 
  

 ### Please click on the link below to see how to use this application.

 [Video on how to use this application](https://drive.google.com/file/d/1-vp799k_4q_l3fIP7Fbuqu0ZeAnYiUim/view)  

  ## License
  
    This project is covered under the Apache license. To learn more about what this means, click the license button at the top.
  http://www.apache.org/licenses/LICENSE-2.0

  ## Contributing
  [Contributor Covenant](https://www.contributor-covenant.org/)  
  To contribute to this project, clone the repo, and then create a new branch. Once you have made your necessary edits, then push to submit a pull request. The contribution will be merged to the main branch after being tested and approved

  ## Tests
  You may test this application using your own information. 

  ## Questions?
  ### Please reach me here: 
  [My GitHub: Jpalomo92](https://github.com/Jpalomo92)  
  Jpalomo92@gmail.com