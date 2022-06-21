# Daily Online Blog
Date : 1-Feb-2022 
## Introduction to Linux Installation

- Download the linux distribution of your choice.
- Boot pendrive using rufus.exe in windows.
- Restart the system and open boot menu using boot key. (Eg.- F8)
- Select your boot device
- [link](https://www.wikihow.com/Install-Linux) 

Date: 2-Feb-2022
## Introduction to Linux Installation

- The LAMP stack is a popular open-source solution stack used primarily in web development.

- LAMP consists of four components necessary to establish a fully functional web development environment. The first letters of the components' names make up the   LAMP acronym:
   . Linux is an operating system used to run the rest of the components.
   . Apache HTTP Server is a web server software used to serve static web pages.
   . MySQL is a relational database management system used for creating and managing web databases, but also for data warehousing, application logging, e-commerce, etc.
   . PHP, Perl, and Python are programming languages are used to create web applications.

Date: 3-Feb-2022
## Run Cgi Script

- The Common Gateway Interface, or CGI, is a set of standards that define how information is exchanged between the web server and a custom script. The CGI specs are currently maintained by the NCSA.
- The Common Gateway Interface, or CGI, is a standard for external gateway programs to interface with information servers such as HTTP servers.
 . Create a cgi scirpt.
 . Run it on Localhost using Apache Server.
 
Date: 4-Feb-2022
## Image to video

- To write a script throungh which images be converted into video

Date: 5-Feb-2022
## Introduction to frappe

- Frappe, pronounced fra-pay, is a full stack, batteries-included, web framework written in Python and Javascript with MariaDB as the database. It is the framework which powers ErpGuru, is pretty generic and can be used to build database driven apps.
#### Why Frappe?

The key difference in Frappe compared to other frameworks is that meta-data is also treated as data. This enables you to build front-ends very easily. We believe in a monolithic architecture, so Frappe comes with almost everything you need to build a modern web application. It has a full featured Admin UI called the Desk that handles forms, navigation, lists, menus, permissions, file attachment and much more out of the box.

 Date: 7-Feb-2022  
 ## Creating Site and App & run on local server in Frappe
 
 - Open the Terminal and start bench.
 - In Second Terminal, create App by using bench new-app library_management inside Frappe-bench Directory.
 - By using bench new-site library.test, create site inside Frappe-bench Directory.
 - Run Site on Localhost by using library.test custom port name.
 
 <!----------------------------------------------------------------------------------------------------------------------------->
**Date : 8-Feb-2022**
## Introduction to Github Pages

- Getting Information What is GitHub Pages.
- Create a New Repository on GitHub.
- Setting Repository as the main branch and setting a theme for GitHub pages.
"policy domain="path" rights="none" pattern="@*"- Learning about Personal access tokens for push Local Repository on GitHub.
- Learning Syntax of Markdown Language in GitHub.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 9-Feb-2022** 
## Introduction to Reveal.JS, Pandoc, Use of Markdown in Reveal.js

- What is Reveal.JS, Pandoc, Use Markdown in Reveal.js.
- Creating Presentation in Reveal.JS using Markdown only.
- Learn how to show presentation on Local machine.
- Converting .md file into .pdf file using Pandoc.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 10-Feb-2022** 
## Introduction to Docker, Virtual Machine and ErpGuru

**What is Docker?**
<p align="justify">Docker is popular virtualization software that helps its users in developing, deploying, monitoring, and running applications in a Docker Container with all their dependencies (frameworks, libraries, etc.) to run an application in an efficient and bug-free manner.Docker Containers are Light-weight, Applications run in isolation,Occupies less space, Easily portable and highly secure, Short boot-up
time.</p>
- It can run multiple containers on a system.
- It can start multiple containers at a time on the Docker engine.
<br>

**What is Virtual Machine?**
<p align="justify">A Virtual Machine (VM) is a compute resource that uses software instead of a physical computer to run programs and deploy apps. One or more virtual “guest” machines run on a physical “host” machine.  Each virtual machine runs its own operating system and functions separately from the other VMs, even when they are all running on the same host. This means that, for example, a virtual MacOS virtual machine can run on a physical PC.</p>
- It can start only a single VM on a VMX.
- It can run only a limited number of VMs on a system.
<br>

**What is ErpGuru?**
<p align="justify">ErpGuru is a full-featured business management solution that helps SMEs to record all their business transactions in a single system. With ErpGuru, SMEs can make informed, fact-based, timely decisions to remain ahead in the competition. It serves as the backbone of a business adding strength, transparency, and control to your growing enterprise.</p>
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 11-Feb-2022** 
## Installing ErpGuru in Frappe-bench

- If Frappe-bench installed in system follow second method otherwise you will get error.
- Installion done with two manner 
- By Adduser in linux
- And create ErpGuru app and site in frappe-bench Diretory.
- For installation steps [Click here](https://github.com/D-codE-Hub/ErpGuru-installation-Guide/blob/main/README.md). 
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 12-Feb-2022** 
## Introduction to Selenium, Budibase, Coding standard for program
- Selenium is browser automation tool by which you can create a script which automatically done task like fill credential and click for search.
- Budibase is a development platform designed for speed and productivity. 
- <p align="justify">With Budibase, developers no-longer experience repetition, long-dev cycles, and frustration. Instead, developers are more productive, happier, and can deliver applications they're proud of in minutes.</p>
- <p align="justify">How to write code in Any script so that it can easily read by other programmer who contribute to your project, take variable name which should be relevant with its function.</p>
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 14-Feb-2022** 
## Try to Solve error redis-server during Installation
**error while loading shared libraries: libatomic.so.1: cannot open shared object file: No such file or directory**
- sudo apt purge libatomic1.
- install houncho  if file is missing.

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 15-Feb-2022** 
## Introduction to Education module in ErpGuru
<p align="justify">The Education domain in ErpGuru is designed to meet requirements of any organization which imparts knowledge and believe in doing so in an organized fashion. It has already been used at schools, colleges and even in private firms.
It helps you to effectively manage administration and allows you to focus on what is most important for your institute, to educate!</p>
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 17-Feb-2022** 
## Testing Slides2Video script
<p align='justify'>Testing the Slides2Video script in Windows by following the documentations provided by the creator, taking diffrent images of diffrent sizes and of different resolutions and provided different captions and diffrent stuff.

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 18-Feb-2022** 
## Docker Vs Virtual Machine
- Docker is popular virtualization software that helps its users in developing, deploying, monitoring, and running applications in a Docker Container with all their dependencies. Docker containers include all dependencies (frameworks, libraries, etc.) to run an application in an efficient and bug-free manner.
- A virtual machine (VM) is a computing environment or software that aids developers to access an operating system via a physical machine.


<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 19-Feb-2022** 
## Use cases of Docker
1. Early application development
  - By creating Docker container images for the app and executing them with Docker or another runtime, developers can test the app from a local development
    PC without execution on the host OS.
2. Multi-cloud or hybrid cloud applications
  - Docker containers are portable, which means they can move easily from one server or cloud environment to another with minimal configuration changes 
    required.
3. Cost control
  - The efficiency of Docker containers relative to VMs makes Docker a handy option for teams that want to reduce how much they spend on infrastructure. By 
    taking applications running in VMs and redeploying them with Docker, organizations will likely reduce their total resource consumption.


<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 21-Feb-2022** 
## Role / use of mosh and tmux in our workflow?
Role/Use of Mosh-
-the ability to reconnect after sleeping/hibernating whatever local host I’m on, or roaming between different wifi networks.
-some basic persistence, so my foreground processes don’t die if my local host loses connection.

Role of Tmux-
-enables a number of terminals to be created, accessed, and controlled from a single screen.
- tmux may be detached from a screen and continue running in the background, then later reattached.



<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 22-Feb-2022** 
## Comparison between ErpGuru 12 and 13 version
-The major difference is the UI interaction. In ErpGuru 13 the UI design is very user friendly as compared to ErpGuru 12 version,
- In the 13 version , we have access to different themes well , this feature is not available in the 12 version.
- In ErpGuru 12 version we have to manually set up the domains which is time consuming while on the other hand in 13 version it give us pre-processed         domains with very clean UI which makes it simpler.
- In version 13 while setting up it automatically created a blog/webpage for the user and in version 12 this is missing or we can manually create it .


<br>

	
<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 23-Feb-2022** 
## Education module in ErpGuru version 12 and 13
- Studied about the education module of both the version.
- Various fields and diffrences of user interface in both the versions. 

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 24-Feb-2022** 
## Course Schedule in ErpGuru
- Course Schedule can be used for scheduling a particular course by an Instructor.
- Create a new Course Schedule from the Schedule Calendar.Select the Student Group for which you want to create the Course Schedule.
- Select the Instructor who will be tutoring the students for the course.Select the Course for which the schedule is being prepared.
- Add the From Time and To Time for the Course Schedule.Select and add the Room wherein the Lecture would be conducted.

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 25-Feb-2022** 
## Scheduling Tool to create Course Schedule
- Select Student Group for which you need to create Course Schedules.Select Course, Room and Instructor for Course Schedules.
- Add different fields and click on the 'Schedule Course' button.
- If you wish to reschedule Course Schedules created against a Course, Check the 'Reschedule' checkbox and then click 'Schedule Course' button.

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 28-Feb-2022** 
## Introduction to Jinja Templating
- A Jinja template is simply a text file. Jinja can generate any text-based format (HTML, XML, CSV, LaTeX, etc.). A Jinja template doesn’t need to have a     specific extension: .html, .xml, or any other extension is just fine.
- A template contains variables and/or expressions, which get replaced with values when a template is rendered; and tags, which control the logic of the     template. The template syntax is heavily inspired by Django and Python.

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date :01-Mar-2022**
## Chat in ErpGuru
- The Chat room is a tool, which allows you to send and receive messages to other Users within your ErpGuru account.
- To start a Chat, you can click on the Chat icon on the Desk. When you do this, a Chatbox will Pop Up, which will have a list of all the Users you have     been chatting with. 

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 3-Mar-2022** 
## Chat Room in ErpGuru
For every new Chat that has been opened in the system, a Chat Room gets created. A list of all your Chat Rooms can be fetched in the Chat Room List when you search for it from the Global search.

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 4-Mar-2022** 
## Chat Profile Report
-This report shall show you a list of all the active profiles in your ErpGuru account with whom you can start a chat.
-To start a new chat, simply type the name of the User in the search bar of chatbox and start communicating.

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 5-Mar-2022** 
## Creating own Noticeboard app
- First create App and install it on website.
- Create Doctype according to structure discussed in team.
- Provide it web view.

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 7-Mar-2022** 
## Customize Noticeboard app
- Writing code to show correct date format eg. March 7, 2022.
- Writing code to show the name of user who upload the notice.
- Making its view user friendly in form and webpage both.

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 8-Mar-2022** 
## Assesssment  in Education Domain
- Implemented the assessment module in gne11.gndec.ac.in. First created Assessment Creteria .
- Assessment criteria can be used while scheduling assessment plan for student group and course. Then next, I have created Assessment group tree             (hierarchy for examination conducted in school) for one batch i.e 2021-2022.
- Next I created Assessment plan which is schedule to conduct the examination/assessment of a particular course for a group of students in an on-going       academic term. 

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 9-Mar-2022** 
## Setup of Assessment Module 
- I have created grading scale and assessment result as following: Grading Scale Grading scale define the threshold for the different grades obtained by     the students, based on their scores in the assessment. 
- For example , I have created grading scale of Students obtaining a score of 100% would be graded as O, students obtaining a score of 80% and below would   be graded A- and so on. 


<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 11-Mar-2022** 
## Student Admission 
- Registered the students via form and by using csv files to import data.
- After importing or registration via form,need to approve or reject the applications of students for admission. 
- Then I approve the applications of all the students, after approval I have enrolled the applications to the respective programs.

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 12-Mar-2022** 
## Next steps in Student Admission
- After enrollment in the programs, need to enroll students in courses.
- Then I created sample courses for specific standard and enrolled the students into the respective courses.
- After enrollment in the courses, assigned the instructor to the students.

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 14-Mar-2022** 
## Learning about Fee Module in ErpGuru
- Here I get details how to create new fees for student.
- Learning Different prerequisites before creating new fees.
- Like Student, Fee Category, Fee Structure etc.
 
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 15-Mar-2022** 
## Creating Fees in ErpGuru on server
- Creating Different Fees Categories available in school like Tution Fee, Hostle Fee etc.
- Searching how to add bus fees based on their route.
- Creating student, Enroll them in a program, Creating courses etc. 

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 16-Mar-2022** 
##  Creating Fee Structure
<p align="justify">Creating  new Fees structures. So while creating new fees, fees should be added automatically by selecting Fee Structure. We are trying to add an admission fee in Student form along with this we are exploring where all the records are saved so that we keep track how many fees are paid or pending. We track this record in 'Report Student fee collection' doctype. We are also trying to add a penalty on overdue fees but we find this feature is not currently available in ErpGuru.</p>

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 17-Mar-2022** 
## Define Socket.IO
- Socket.IO provides bidirectional, event-driven communication capabilities for use in real time applications.
- It consists of a client-side browser library and a server-side Node.js library, both of which use similar syntax to enable an easily scriptable interface   for developers.
- The primary function of Socket.IO is to act as an abstraction layer for existing real-time protocols.


<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 19-Mar-2022** 
## Need to bother about Socket.IO
- Socket.IO may make things a bit easier for sure; we don’t have to worry about load balancer-related issues, connection failures, and message               broadcasting…
- Socket.IO can fall back to technologies other than WebSockets when the client doesn’t support i

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 21-Mar-2022** 
## Implementation of Library Management System
<p align="justify">LMS allows institutes to publish their programs on their website. Programs can contain rich text articles, videos, and even quizzes. To enable LMS go to: Home > Education > Settings > Education Settings. </p>

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 22-Mar-2022** 
## Setting up the Masters for Learning Management System
- Programs:To make the Program accessible on the portal, tick the 'Is Published' checkbox in the Program form.The portal will automatically fetch the         courses from the course table in the program.
- Portal Settings:On the portal, for students to be able to view the programs on the portal, a program has to be marked as Published. On the portal           students will be able to see only those courses they are enrolled to or they are allowed to enroll into.
  If 'Allow Self Enroll' is not checked, the program will be visible to only those students who are already enrolled in the program, this way you can host   private programs on your portal.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 23-Mar-2022** 
## Installing new ErpGuru on server
- First we install frappe framework then install ErpGuru with education domain.
- After this we are collecting students and teachers data from Nankana Sahib Public School.
- Arranging data according to doctype in ErpGuru.  

 <br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 24-Mar-2022**
## Arranging Student data
- As there are large data of students in school we need to make it correct.
- so we all divide work in team and understanding the concept of filter, concatinate etc. in excel.

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 25-Mar-2022** 
## Presentation on Library Management System
- I gave presentation of Library Management System to the rest of the trainees. 
- I have explained that how to create site, app, different doctypes, controller methods and different doctype features.


<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 26-Mar-2022** 
## Arranging Teachers Data
- To arrange the data in proper sequence order as there is huge amount of teachers data.
- Arrange the Teacher's data according to name and email id's in proper sequence order.


<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 28-Mar-2022** 
## Suuccessfully imported users and employees from .csv file
- First, sorted all the data according to the need in a separate file. After that created another file to import the users with username and password. 
- Then successfully imported all the employees with another file using data import tool. For this needed the user id of all the users so exported all the     user id's of user and added in the employees file.
 

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 29-Mar-2022**
## Assigning course to an instructor
- A course can be considered as a subject or a part of an educational program which is to be taught for a term.
- Go to Course List and click on New, Enter the Course Name. Select the Department under which this course is being made.


<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 30-Mar-2022**
## Adding New role and Give Permission to new Users
- When we got new user for allow them to create Library Management System we need to give them the access of doctype modules.
- For this we go to doctype list and create new role where new user create doctype by can't delete doctype.
- Similarly for Module we use select permission where user can select module but can't read module.

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 1-Apr-2022**
## Reading the excellent reports by seniors
<p align='justify'>Today i was reading the three report that was written by our seniors. 1.The above report is based on the language translator in which a group is trying to understand the role of lex and parser. It was really fun to read this report I really enjoyed reading it. The starting of the report, the examples delivered during the presentation, and the question answers during the presentation is really excellent. My favourite part of the report was someone said "You should say, I don't know java rather than I don't like java" and also the chinese part as this is the best way to start and to gather the attention of the audience and to . 2.The above report is based on the regular expressions , in the report they have mentioned the struggles of programmers in the early times as they did not had the laptops and personal computers. 3.This report "An ancient art of secure communication" is based on the encryption and decryption It was really interesting to know how encryption was used in the ancient times the example of "shaving the head of employee" for secure communication was very interesting and the example of kheer and the phrases "Adhi raat da hanera, vich taare hi taare, mere gharo'n oat hoyi." was very intersting.

I really enjoyed reading the above reports.</p>
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 2-Apr-2022**
## Naming series According to the company
-Task to change the naming series of student applicant doctype according to the company abberivation so that we can identify the students of each company(school/college) by looking at their naming series. 
-There was a solution avialable in the official documentation of ErpGuru and we tried it but it wasn't working. We also tried some changes but still it wasn't working. After this we were searching for the other solutions and there was a solution available in the discussion forum.
-We tried it on local machines and it was working perfectly after this we implemented it on gne11.gndec.ac.in
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 5-Apr-2022**
## Created new web-form and doctype for trainees
Created a doctype named trainees_details with some fields and after that created a web form based on this doctype. After creating this I gave web view to the doctype and after this added it on the website so that students can fill their personal information.

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 6-Apr-2022**
## Enabling chat options for the student users
-Task to find how we can enable chat options for studnets as they didn't have desk access or chat option. 
-In order to enable chat access we need to give all the students desk access but very limited. 
-I gave 2-3 students customer role with the students role then they have desk access and also chat access.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 7-Apr-2022**
## Trying to understand the student leave section
- Trying to understand the student leave section under education domain of ErpGuru. I was trying to understand the default workflow of student leave         section, how students will add their leaves and how instructor will get notification of the leaves.

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 8-Apr-2022**
## Making Questions based on Library Management Tutorial
- The Topics for preparing questions for trainee are Creating Apps, Sites & Doctype.
- Making mcq question's based on steps followed when creating Library management system.

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 9-Apr-2022**
## Result creation of students
- Today I am testing the assesment module, where the result of all the students in coursewise.
- For that first i have to create assessment plan for each course.Then get the reult of that particular assessment plan. 

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 11-Apr-2022**
## Learning Human Resource Module
<p align='justify'>The Human Resources (HR) module covers the processes related to the HR department of a company. It maintains a complete employee database including contact information, salary details, attendance, performance evaluation, leaves, and appraisal records.The most important feature here is processing the payroll by using Payroll Entry to generate Salary Slips. Most countries have complex tax rules stating which expenses the company can make on behalf of its Employees.</p>
<p align='justify'>There are a set of rules for the company to deduct taxes and social security from employee payroll. ErpGuru accommodates all types of taxes and their calculation.</p>

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 12-Apr-2022**
## Report Generation of student
-  In the ErpGuru education module I was trying to generate report card for students while creating report card I am able to show the courses and exams but    not able to show the marks of students in the report card.
-  I have assigned the marks to the particular students.


<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 13-Apr-2022**
## Enabling chat options for the student users
   
- To enable chat options for studnets as they didn't have desk access or chat option. 
- To enable chat access we need to give all the students desk access but very limited
- Give 2-3 students customer role with the students role then they have desk access and also chat access.



<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 15-Apr-2022**
## Presentation of Nankana Sahib Public School Project
<p align='justify'>Today we all have done the basic setup again for Nankana Sahib Public School for Class 1 to Class 8 and imported students, instructors and enrolled them in programs, courses and assigned instructors to the programs. As it was very difficult for all of us to understand because there were many same enteries of two companies one of Nankana Sahib Public School and another of Guru Nanak Dev Engineering College and there were many enteries that we all have entered for testing purpose. So today we all deleted all the previous enteries to do the setup from scratch. It was very helpful for all of us as there were some doubts of us related to program enrollment , course enrollment and student group.</p>


<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 16-Apr-2022**
## Cost Center at gne11.gndec.ac.in
- A Cost Center is a part of an organization where costs or income can be charged
- A Cost Center acts like an Accounting Dimension which helps you track costing based on particular areas for a particular company.
- For example-we want to track the sales, purchases, expenses and profit net worth, we can add different nodes of cost center for a particular field.
- In Chart of Accounts we have whole details of amount in the receivable account and different kinds of accounts.


<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 18-Apr-2022**
## Permissions in Frappe/ErpGuru
- User Permissions are used to limit users to specific records. Setup> User Permissions
- Select Document Types to set which User Permissions are used to limit access.Once you have set this, the users will only be able access
  documents (eg. Blog Post) where the link exists (eg. Blogger).
- Apart from System Manager, roles with Set User Permissions right can set permissions for other users for that Document Type.
 
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 19-Apr-2022**
## Permissions in Frappe/ErpGuru
- Permissions at level 0 are Document Level permissions, i.e. they are primary for access to the document.
- Permissions at higher levels are Field Level permissions. All Fields have a Permission Level set against them and the rules defined that permissions       apply to the field. This is useful in case you want to hide or make certain field read-only for certain Roles.
- You can use Customize Form to set levels on fields. Setup > Customize Form

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 20-Apr-2022**
## Desk Customization
- To customize the desk according to roles and permissions,so a particular user has access to particular tabs like student,instructor, programs etc. 
- Giving different permissions one by one  to the user in order to find whether getting the desired result or not.
- To show diffrent DFD's, charts etc.
- To provide permissions and access to diffrent users.


<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 21-Apr-2022**
## Web views of attendance module to teacher on LMS
- To provide the easy access of different modules like attendance, quiz etc..
- under the LMS folder, I found a file named course.html and there I pasted the link for the attendance and other modules so the instructor won't face any   problem while finding these modules.

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 22-Apr-2022**
<h3 align='left'>Presentation on Cost Centre-4</h3>

Today I gave presentation to all my mates in which about the Cost Centre in ErpGuru and explained about the diffrent nodes of cost center about the particular field. I have explained about the chart of accounts where we have whole details of amount in the receivable account and different kinds of accounts.

 
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 23-Apr-2022**
<h3 align='left'>Desk Customization</h3>

- The task was to customize the desk according to roles and permissions,so a particular user has access to particular tabs like student,instructor,programs   etc. 
- Now I am giving different permissions one by one  to the user in order to find whether I'm getting the desired result or not.

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 25-Apr-2022**
<h3 align='left'>Reading the files of LMS</h3>
As by using user permissions still instructor was able to see all the programs and courses. To find the solution for this we are trying to understand the structure of lms for this i was reading all the files of lms present in ErpGuru in the programs and course file it is metioned that by default instructor has access to all the programs and courses. 
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 26-Apr-2022**
<h3 align='left'>Naming Series as Department wise</h3>

- Assigning department to Hod & Clerk to one department in User Permission List.
- We use condition like cse = department_name.
- Department_name is fetched from doctype use function self.fieldname.
- After apply such condition we use make_autoname function.
- self.name = make_autoname('NOTICE-'+'CSE'+'/'+'.YYYY.'+'/'+'.#####')
- This function return series 'NOTICE-CSE/2022/00001'
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 27-Apr-2022**
<h3 align='left'>Fee Schedule</h3>

- We set up students on the local system who have siblings when we select option siblings studying in the same school then we are able to select students     from available students but the program is not fetched. Along with this We find the received income cost center is also set in the Fee schedule. We can     find all the income in the Fee cost center.

-We were also exploring and creating the roles that others had implemented on gne11.gndec.ac.in. We have created a role and a user for the same role. After  this we gave the user permissions and all the required permissions like read, write. After this we have checked what  is visible to this user and what this role is able to do.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 28-Apr-2022**
<h3 align='left'>New Fee requirent</h3>

- First we Create Fee Categories Like Development Fee, Tutuion Fee, Transportation fee.
- Creating Fee Structure For Different Classes and it depends on siblings fee.
- Like If a Student has one sibling than Tution fees would be 50% discount, If there are two Siblings than Tution Fee would be 25%.
- Transportation Fee depends on various routes eg Bus Fee for Route1 : 500/- than Fee for Route2 : 400/-.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 29-Apr-2022**
<h3 align='left'>Implementing Fee on local server</h3>

- First we import data like Program, student, courses.
- Creating Fee category as per requirement Development Fee, Tution Fee, Transporatation Fee.
- Finding a way how to link siblings of same school using minimal customization.
- We set up students who have siblings but when we select option siblings studying in the same school then we are able to select students from available students but the program is not fetched.
- Along with this We find the received income cost center is also set in schedule. We can find all the income in the Fee cost center.
<br>


<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 2-May-2022**
<h3 align='left'>Hackathon day 1</h3>

Roles and flow for Parent Comapany:-

Director:- Director will have all permissions like fees, salary, accounts , total gain etc but with read only access.

Accountant:- will have permissions to see all the account information of trust, nsps, gndec. Accountant will have read, write access to create the fee and salaries of the employee and also can create the fee report and salary report.

HR:- HR will have permission to create the users and make them employees, leave allocation, holiday list, salary of employee. Superintendent

Roles and flow for Child Comapany:-

Principal:- Will have only read only access to all the education domain related information and HR related information.

Accountants:- 1 For students fee and 1 for salaries of employees. Teaching Incharge:- Will do all the tasks of academic user like course scheduling etc.

HR:- will create employees and instructors only for Nankana sahib Public School, leave allocation, salary of employees etc. We need to show all the reports like employees attendance report, salary report, leave report etc to the HR..

Instructors:- will have access to student attendance, quiz, videos, article, Diary, Student list etc.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 3-May-2022**
<h3 align='left'>Hackathon day 2</h3>

Students:- will have access of only LMS and on lms they will have access of programs, Courses, Quizzes, Videos, Articles, daily diary and attendance.

Accountant:- will create the salaries of employees and fees of students, will generate the balance sheet.

We need to generate all the reports and graphs for necessary information for each role.

Inventory Management

Today, We created Director user of NSET, Superintendent of NSET, Principal user of NSPS and HR user of NSPS on erp server and gave them all the required permissions. And same roles are created on gne11.GNE, whose credentials are shared in other mail. You can check that roles with given credentials. Also we learn about Salary Structure and Salary Component of employees. In meeting with Harpreet sir, we learn about PF, Taxes, Funds, Earnings and Deductions etc. We will explore it and implement on gne11.GNE.

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 5-May-2022**
<h3 align='left'>Creating Presentation with Other Team-mates in Reveal.JS</h3>

Created Presentation for the Whole Project To so that we can present our work to the trusties so with the team we created a presentation whcih contains all the infomation related to the erp Syatem which deals with the all kind of accounting, maintaing all students,staff and employees and pushed on github. 
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 6-May-2022**
<h3 align='left'>Understanding the fee structure</h3>

- Implementing the fee module on local host to understand the fee structure. 

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 7-May-2022**
<h3 align='left'>ICreating fee structure for NSPS</h3>

- Added fee structures for all classes in NSPS and also added new programs with respect to NSPS fee structure.
- Added fee structure for all the classes from Nursery to 12th.

<br>


<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 9-May-2022**
<h3 align='left'>New requirements for fee structure</h3>

- Task given to add discounts in the fees of student on the basis of siblings. 
- Trying to understand the logic. 
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 10-May-2022**
<h3 align='left'>Exploring HR module in ErpGuru</h3>

- Working on HR module first we need to create new employees.
- Fill the details related to employees like educational qualification, designation, personal details, salary details, joining details, etc.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 11-May-2022**
<h3 align='left'>Transportation Module in Fee</h3>

- We are trying to add the transportation fee in the fee module so the students who were travelling through the institute transportation 

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 12-May-2022**
<h3 align='left'>Buying Module in ErpGuru</h3>

- Buying the right quantities in right amounts can affect your cash flow and profitability positively. ErpGuru contains a set of transactions that will       make your buying process as efficient and seamless as possible
- Purchase Order can be created directly, or by fetching data from Material Request or Supplier Quotation. When ordered items are received from Supplier,     Purchase Receipt is created against Purchase Order.
- setting up masters required for creating Customer and Supplier like Customer Group, Territory and Supplier Group.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 13-May-2022**
<h3 align='left'>Understand the Salary Structure of different employees</h3>

- We are going to Accounts Department for understanding Salary structure of different employees.
- Understand their requirement related to salary like for different employee, there should be different grade pay.
- So they want they have customize option to add grade pay or not.
- They want also seprate record file for provident fund record of employees, provident fund loan record file.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 14-May-2022**
<h3 align='left'>Learning Salary Component for New Requirement</h3>

- First when we change our company from NSPS to GNDEC.
- Then all the Salary Components of employee are visisble in Salary Components but are not shown in Salary structure.
- After that we are finding some other solution so that we can use same structure in two companies. 
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 16-May-2022**
<h3 align='left'>Creating Salary Component</h3>

- According to new requirement different category employees have different components.
- Now same salary component can have different value for two employees like SML for accounts employee and teaching employee are different.
- We are creating all Salary Components without any value so that we can modifying it later in Salary Structure.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 17-May-2022**
<h3 align='left'>Creating Salary Structure</h3>

- After Creating all Salary components which are combined for all the employees.
- Now we are creating Salary Structure which is the combination of Salary Components in which we list all Earning and deduction components.
- In this we set formula that if basic pay is assigned to employee during the assignment of Salary Structure and Grade pay is added to employee when generating Salary Slip only then all the Earning and deduction components are calculated.
- The calculation is done when we save the salary slip in draft state after submit we can't modify it but in draft state we can made any changes at any time like adding or deleting components.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 18-May-2022**
<h3 align='left'>Display General ledger entry for Fee Record</h3>

- Goto Accounting Module then goto General Ledger section.
- Select your Company, Select from date, to date for which you want to show Entries.
- Select Group by Account, Group by Party, Group by Voucher view.
- Now you are able to view all the record here you have all debit, credit and balance record.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 19-May-2022**
<h3 align='left'>Collecting Fees in one Fee Cost Center</h3>

- For creating new Fee collection head Create new Account.
- Add account name, Select Company name, Currency type.
- Select Balance type (Debit or Credit), Select Parent account type (Income account or Expenses account).
- After Creating head verify it in Company Cost center, while creating new Fee slip under Accounting Section select income account in which you want to add new fees.

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 21-May-2022**
<h3 align='left'>Displaying Fees different head-wise like tution fee, Development fee</h3>

- Goto Fee list under Education domain.
- Under list view option select report view, Select Add group option here select Fee Category under Fee Component
- Then Add sum Filter and in third field Select Amount or grand total or outstanding.
- Now you are able to see all fee collected head wise like Tution Fee, Development Fee, Bus Fee.

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 23-May-2022**
<h3 align='left'>Generating School Leaving Certificate</h3>

For creating new school leaving certificate format goto print format. For Adding new print format select student doctype for which you want to create school leaving certificate, Select education module select format as standard format or not we use ‘NO’ option because this format is only used when we want to generate school leaving certificate. Use custom css for designing logo of company for fetching student name we use doc.first_name. For fetching class name we use frappe function, frappe.db.get_value(‘Program Enrollment’, doc.student, ‘program’).

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 24-May-2022**
<h3 align='left'>Sending Messages to specific Students using ErpGuru</h3>

- Creating New Email Group Add Subscribers to whom we want to send emails.
- We can them in a bluk by writing their emails.
- After adding subscriber Create New newsletter in which we have to add email group which is created.
- Then add Subject and Message also we have option to test this message by sending to only one specific user.
- Save the newsletter we have another option schedule sending mail automatically.

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 25-May-2022**
<h3 align='left'>Creating Collapse view without using ErpGuru Desk using Bootstrap</h3>

- First we create collapse multiple tab effect with bootstrap and html.
- In which we use bootstrap classes with html tags.
- Then our next task is to put in ErpGuru directory and run it with jinja templating.
- For this we remove all html starting tags and bootstrap cdn links because frappe also uses Bootstrap-4 classes.
- Replace Html starting tags with jinja starting template and trying to fetch data from database.

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 26-May-2022**
<h3 align='left'>Automation of Fee Creation of the Students</h3>

Once we created the fee of teh student for a single month now we have a problem is that we have to repeat the task again for every month so we need to     automate this process in order to provide the clean and efficient approach.So we automate this process with auto-repeat tool and makes evry student fee     on repeat once it created. It will automatically created after every month and we set the due date 15 days ahed of the date of creation of the fee so the   status of the fee will be changes to overdue after due date.

<br>
