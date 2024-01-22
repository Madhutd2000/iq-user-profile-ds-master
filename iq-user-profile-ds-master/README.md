"# iq-user-profile-ds" iQ is a software solution offered by Worldpay from FIS to its merchants.

----- Project Setup -----

Install Latest sts, Maven and Java-11

Create a new folder in File Explorer to house the project locally

Copy the file path of the created folder

Open command prompt, and navigate to the directory of created folder a. "cd C:/file/path/here"

In browser, navigate to the project's repository a. https://github.worldpay.com/Worldpay/iq-user-profile-ds

Scroll down until you see a green button labelled "Clone or Download" on the right-hand side of the screen a. Copy this given URL

In command prompt, clone the project with the given URL a. "git@github.worldpay.com:Worldpay/iq-user-profile-ds.git" b. This will add the project to your folder you created locally c. Note, this may ask you for a password. This will be your Github password

Enter the project's directory a. "cd iq-user-profile-ds"

import the files using "existing maven project"

download the application.properties file and copy paste under src/main/resources

open the command promt and run "mvn clean install"

mvn will build successfully then you can right click on project and run as "Spring boot app"


----- Git Cheat Sheet ----- 

For help with Git commands, visit the document below https://education.github.com/git-cheat-sheet-education.pdf
