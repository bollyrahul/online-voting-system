# online-voting-system

Project Report
on
[Online Voting System using PHP]
Submitted to
LOVELY PROFESSIONAL UNIVERSITY
for
[INT220] [SERVER-SIDE SCRIPTING]



Submitted By								Submitted to
[RAHUL NAYAK]							Navneet Kaur
[11907485]								Assistant Professor



LOVELY FACULTY OF TECHNOLOGY & SCIENCES
LOVELY PROFESSIONAL UNIVERSITY
PUNJAB
April 2022





Table of Contents

Chapter	Particulars								Page No.
Chapter 1. 	Introduction……………………………………………………………..3
Chapter 2. 	Technologies used………………………………………………………4
Chapter 3. 	Modules………………………………………………………................5
Chapter 4. 	Website snapshots………………………………………………………7
Chapter 5. 	GitHub link………………………...........................................................14
Chapter 6. 	References……………………………………………………………….14
 
CHAPTER 1
INTRODUCTION
1.1	Introduction about the project
Online Voting System concept to use our knowledge of programming to create a system that can be used by the users to cast their votes online. They can be able to see the list of nominations as well. Moreover, using the database, we can also add the feature of store the entered votes and hence this website can function as a full-fledged vote counting system too, where votes can be counted as we enter the data. Hence, this project is called the online voting system.

1.1.1	Features of the Project
This website has the following features:
•	User is able to cast their votes to the listed parties.
•	Only one vote can be casted per user.
•	User has to login to validate his candidature.
•	Admin’s panel to see the count of the casted votes.
•	Nomination’s list that contains the information of the candidates.
•	Responsive Home Page
1.1.2    Drawbacks of the Project 
Due to time-constraint this website has the following drawbacks:
•	Same user can create multiple ids.
•	Voter ID definition not defined.
•	Website could be more colourful.









CHAPTER 2
TECHNOLOGIES USED IN THE PROJECT
Online Voting System concept to use our knowledge of programming to create a system that can be used by the users to cast their votes online. In the making of this project, following technologies are used.

         2.1 HTML
HTML is used a basic backbone of the website designing. HTML is a great tool to make webpages like this.

         2.2 CSS
CSS is used to graphically enhance the look of the website to make it more user friendly.
 
         2.3 PHP
PHP is our main server side scripting language used in this project to make the backend of this website.

         2.4 JS
JavaScript adds the necessary functionality to the website. 

         2.5 SQL
The MySQL helps to store the data in the server and retrieve the data as or when demanded by the user in this website. 






CHAPTER 3
MODULES
Online Voting System website has the following modules in the project:

3.1	Home Page
This module of the website contains of the homepage of the main landing page. This contains the option/button to cast you vote. Once you click this button it will take the user to the Voting page (refer to 3.2) directly. Scrolling down the page we will get to the general information section of the webpage which highlights the key features of the website followed by the footer part of the webpage which contains my name. This part is responsive.

3.2	Voting Page
Just like the home page this page is also responsive. From the home page once a user decides that he/she wants to cast their vote they can click on ‘cast your vote’ from   the home page and then they will be redirected to this voting page. It has a few details to fill to validate your candidature and once the details are verified, one can cast the vote from the list of parties. Their votes will stored in the SQL Server  (refer to 3.7) created for the same purpose.

3.3	Admin Login Page
Once the voting process is over, the next logical step is to check the voting count or the election results. This page allows the admin to enter his/her user-id and password to get access to his Admin’s Dashboard (refer to 3.4). This page protect malicious users from entering the admin’s dashboard. Only authorized user can enter.

3.4	Admin’s Dashboard
Once the voting process is over, the next logical step is to check the voting count or the election results. Though the SQL Server (refer to 3.6) has all the details of the same, the admin’s dashboard is the best pace to view the voting counts. The votes are displayed in number and in bar graph format.


3.5	Nomination’s List Page
From the Admin’s Dashboard, the admin can go to the Nomination’s list directly and see the list of candidates who are fighting the elections and the general details about them.

3.6	Change Admin Password Page
Incase the admin feels that his/her password is compromised they can change their password from this page.

3.7	SQL Server
The SQL server stores all the data used in this project. Firstly, it stores the admin password and helps in validating the admin. Secondly, it holds the list of users along with their personal credentials and validates them during the process of voting. Lastly it also holds the total voting data during the vote casting process.





 
CHAPTER 4
WEBSITE SNAPSHOTS
Here are the snapshots of the website and its various modules and its working.












         (Screenshot of XAMPP Control Panel with Apache Server and MySQL enabled)

         4.1 Home Page
       












(Snapshot of Homepage…Part 1 with Cast Your Vote Button)













(Snapshot of Homepage…Part 2 showing the features of the website)


















(Snapshot of Homepage…Part 3 shoeing the footer)













(Snapshot of Homepage showing that the website is completely responsive)

4.2	Voting Page













(Snapshot of Voting Page with the form asking for details of the voter)
















      
      (Snapshot of Voting Page with sample data)


















        (Snapshot of Voting Page after vote is successfully casted)

4.3	Admin Login Page













(Snapshot of Admin’s Login Page with sample values entered)

4.4	Admin’s Dashboard














(Snapshot of Admin’s Dashboard with the Voting Results)

4.5	Nomination’s List Page













(Snapshot of Nomination’s List Page)

4.6	Change Admin Password Page













    (Snapshot of Admin’s Password Page)


4.7	SQL Server













(Snapshot of SQL Server with the saved table)















(Snapshot of SQL Server with the saved voter data)


CHAPTER 5
GITHUB LINK
Online Voting System, the project that was made by me is saved on gtihub and anyone on the internet can access the same using the following link:
https://github.com/bollyrahul/online-voting-system

Total Commits: 10

  








CHAPTER 6
REFERENCES
This project of Online Voting System would not have been possible without the guidance of Navneet ma’am. I got a great deal of help from the internet also and watching tutorials on YouTube also helped in getting my project done on time.

•	YouTube Tutorails
•	Stack Overflow
•	Github
•	PHP (W3 Schools)





