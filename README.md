# CSI-Project-Report
Progress of the CSI Project.

## Week 1
- Completion of the assignments of freeCodeCamp on NodeJS and MongoDB

## Week 2
- Started with exercises of JS on freeCodeCamp.
- Created github repository for the project.
- Cloned the theme template
- Edited the template
- Read articles on handlebars and express

After these two weeks, I started working on the main repository for the projects Cybros-Web-Application (https://github.com/OpenSouce-LNMIIT/Cybros-Web-Application). I started with solving Issue #114, that was adding the feature of Password Hashing which was missing earlier.

To solve this issue, I added the package 'password-hash'. It is a NodeJS library to simplify use of hashed passwords.

Next, I started adding the new UI template to the project beginning with the header and footer.

After I started working on a new issue which was adding environment variables for email notification. Solution for this included installing the npm package dotenv and then creating a file .env which will include the email id and password which were earlier included in the app.js file.
In the app.js, I included the package and created a local variable for the same. In signup.js, I replaced the email-id and password with the environment variables mentioned in the .env file.

After this, we began working on integrating the template. Beginning with the partials(headers, footer, and adminheader). After updating the partials template, we began updating the template for the home page, about us and administrator's dashboard.

## After First Submission 
- Updated all the views to the new template. (https://github.com/OpenSouce-LNMIIT/Cybros-Web-Application/pull/125)
