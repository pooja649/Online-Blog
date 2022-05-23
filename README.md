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

- Frappe, pronounced fra-pay, is a full stack, batteries-included, web framework written in Python and Javascript with MariaDB as the database. It is the framework which powers ERPNext, is pretty generic and can be used to build database driven apps.
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
## Introduction to Docker, Virtual Machine and ERPNext

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

**What is ERPNext?**
<p align="justify">ERPNext is a full-featured business management solution that helps SMEs to record all their business transactions in a single system. With ERPNext, SMEs can make informed, fact-based, timely decisions to remain ahead in the competition. It serves as the backbone of a business adding strength, transparency, and control to your growing enterprise.</p>
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 11-Feb-2022** 
## Installing ERPNext in Frappe-bench

- If Frappe-bench installed in system follow second method otherwise you will get error.
- Installion done with two manner 
- By Adduser in linux
- And create Erpnext app and site in frappe-bench Diretory.
- For installation steps [Click here](https://github.com/D-codE-Hub/ERPNext-installation-Guide/blob/main/README.md). 
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
## Introduction to Education module in Erpnext
<p align="justify">The Education domain in ERPNext is designed to meet requirements of any organization which imparts knowledge and believe in doing so in an organized fashion. It has already been used at schools, colleges and even in private firms.
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
## Comparison between ErpNext 12 and 13 version
-The major difference is the UI interaction. In ERPNext 13 the UI design is very user friendly as compared to ERPNext 12 version,
- In the 13 version , we have access to different themes well , this feature is not available in the 12 version.
- In ERPnext 12 version we have to manually set up the domains which is time consuming while on the other hand in 13 version it give us pre-processed         domains with very clean UI which makes it simpler.
- In version 13 while setting up it automatically created a blog/webpage for the user and in version 12 this is missing or we can manually create it .


<br>

	
<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 23-Feb-2022** 
## Education module in ErpNext version 12 and 13
- Studied about the education module of both the version.
- Various fields and diffrences of user interface in both the versions. 

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 24-Feb-2022** 
## Course Schedule in ErpNext
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
## Chat in ErpNext
- The Chat room is a tool, which allows you to send and receive messages to other Users within your ERPNext account.
- To start a Chat, you can click on the Chat icon on the Desk. When you do this, a Chatbox will Pop Up, which will have a list of all the Users you have     been chatting with. 

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 3-Mar-2022** 
## Chat Room in ErpNext
For every new Chat that has been opened in the system, a Chat Room gets created. A list of all your Chat Rooms can be fetched in the Chat Room List when you search for it from the Global search.

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 4-Mar-2022** 
## Chat Profile Report
-This report shall show you a list of all the active profiles in your ERPNext account with whom you can start a chat.
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
## Learning about Fee Module in Erpnext
- Here I get details how to create new fees for student.
- Learning Different prerequisites before creating new fees.
- Like Student, Fee Category, Fee Structure etc.
 
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 15-Mar-2022** 
## Creating Fees in Erpnext on server
- Creating Different Fees Categories available in school like Tution Fee, Hostle Fee etc.
- Searching how to add bus fees based on their route.
- Creating student, Enroll them in a program, Creating courses etc. 

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 16-Mar-2022** 
##  Creating Fee Structure
<p align="justify">Creating  new Fees structures. So while creating new fees, fees should be added automatically by selecting Fee Structure. We are trying to add an admission fee in Student form along with this we are exploring where all the records are saved so that we keep track how many fees are paid or pending. We track this record in 'Report Student fee collection' doctype. We are also trying to add a penalty on overdue fees but we find this feature is not currently available in erpnext.</p>

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
## Installing new Erpnext on server
- First we install frappe framework then install erpnext with education domain.
- After this we are collecting students and teachers data from Nankana Sahib Public School.
- Arranging data according to doctype in erpnext.  

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
## Working with Client Script in Form
- Client Script is script in which we add some action on form so that we validate data or do other function.
- Webform script is which is done in webform while creating new webform.
- For Reference we use Web form Scripting Documentation [Click here](https://frappeframework.com/docs/v13/user/en/api/form) 

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 2-Apr-2022**
## Sending Daily report to Student Group
- For Sending daily report in student group First we add student and Intructor in student group with batch name.
- Then we create email group and add students email where we send them email at same time.
- In Student group on view option we create new newsletter with content and add email group then we are able to send email to group of Student.
 
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 5-Apr-2022**
## Trying to create Daily Daity without using email
- For this first we create a doctype.
- Trying to add permission in doctype so that only student group can access these Dairy.

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 6-Apr-2022**
## Creating Library Management System
- As per official documentation I create Library Management App.
- Install app on site then creating doctype.
- Use Features like Naming Series, Permission Rules.
- Learn Controller methods, Doctype Features, Form Scripts.
- Adding Web view for preview Articles on web.

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 7-Apr-2022**
## Trying to make pagination and filter on webpage
- First we are's trying to read built-in frappe file so that we can use it in webpage.
- Make changes in built in files to apply it on global in frappe.

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 8-Apr-2022**
## Making Questions based on Library Management Tutorial
- The Topics for preparing questions for trainee are Creating Apps, Sites & Doctype.
- Making mcq question's based on steps followed when creating Library management system.

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 9-Apr-2022**
## Learning bash script
- As per Questions Created for Trainee it contain different format.
- Then I need to create bash script using sed to find and replace the wrong format symbols.
- The example of sed command is 'sed 's/$ //gI' filename'. 

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 11-Apr-2022**
## Learning Human Resource Module
<p align='justify'>The Human Resources (HR) module covers the processes related to the HR department of a company. It maintains a complete employee database including contact information, salary details, attendance, performance evaluation, leaves, and appraisal records.The most important feature here is processing the payroll by using Payroll Entry to generate Salary Slips. Most countries have complex tax rules stating which expenses the company can make on behalf of its Employees.</p>
<p align='justify'>There are a set of rules for the company to deduct taxes and social security from employee payroll. ERPNext accommodates all types of taxes and their calculation.</p>

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 12-Apr-2022**
## Role and  Permission to new Users
- Allow new users to create Library Management System, need to give them the access of doctype modules.
- Go to doctype list and create new role where new user create doctype by can’t delete doctype.
- Similarly for Module we use select permission where user can select module but can’t read module.



<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 13-Apr-2022**
## Enabling chat options for the student users
   
- To enable chat options for studnets as they didn't have desk access or chat option. 
- To enable chat access we need to give all the students desk access but very limited
- Give 2-3 students customer role with the students role then they have desk access and also chat access.



<br>

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
## Permissions in Frappe/ERPNext
- User Permissions are used to limit users to specific records. Setup> User Permissions
- Select Document Types to set which User Permissions are used to limit access.Once you have set this, the users will only be able access
  documents (eg. Blog Post) where the link exists (eg. Blogger).
- Apart from System Manager, roles with Set User Permissions right can set permissions for other users for that Document Type.
 
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 19-Apr-2022**
## Permissions in Frappe/ERPNext
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
<h3 align='center'>Presentation on Cost Centre-4</h3>
Today I gave presentation to all my mates in which about the Cost Centre in Erpnext and explained about the diffrent nodes of cost center about the particular field. I have explained about the chart of accounts where we have whole details of amount in the receivable account and different kinds of accounts.

 
<br>
<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 23-Apr-2022**
<h3 align='center'>Making new specification and Flow for Noticeboard App</h3>

- Notice will be created by CLERK then it will be in draft state.
- CLERK and HOD can create notice no one else from other department able to create notice for their department.
- Another requirement when notice is created by clerk It will be in Draft state when Hod Submit Notice only then it would be published.
- Naming Series of notice maintained department wise eg: Notice-CSE/2022/00001, Notice-CIVIL/2022/00001.
- If HOD Cancel the notice then Clerk is able to make changes then again send it to HOD.  
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 25-Apr-2022**
<h3 align='center'>Creating doctype in Existing Noticeboard App</h3>

- In First approach we decide to use create doctype and apply workflow on it.
- Where all states are defined like Approve by hod, Draft etc.
- We allote Department to their Respective Hod and Clerk  So that they are able to create notice.
- Every thing Works fine but When we apply some code then workflow states create problem. eg data is saved but changes apply with delay.
- We find workflow also make task for app difficult because its file is not created inside the app that why it portability is difficult.
- So we decide to work without workflow also learn new things from mistakes.   
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 26-Apr-2022**
<h3 align='center'>Naming Series as Department wise</h3>

- Assigning department to Hod & Clerk to one department in User Permission List.
- We use condition like cse = department_name.
- Department_name is fetched from doctype use function self.fieldname.
- After apply such condition we use make_autoname function.
- self.name = make_autoname('NOTICE-'+'CSE'+'/'+'.YYYY.'+'/'+'.#####')
- This function return series 'NOTICE-CSE/2022/00001'
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 27-Apr-2022**
<h3 align='center'>Fetching HOD by using variables in query</h3>

- First we use Simple Frappe query "frappe.db.get_value('User', 'hodcse@gmail.com', 'full_name')".
- But this depends upon the email of hod if email will change in future then we need to change it.
- Also we have to wrote this many times.
- So we use another optimized version of query.
<br>

```py
department = self.department
requiredRole = "Hod" 
		
		self.hod = frappe.db.sql(f""" select full_name 
			from `tabUser` 
			where `email` IN (select user 
			from `tabUser Permission` 
			where `for_value`="{department}" AND `user` IN (select parent 
			from `tabHas Role` 
			where `role`="{requiredRole}" )) """)
```

- By using this query with variable we are able to use this for all departments.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 28-Apr-2022**
<h3 align='center'>New Fee requirent</h3>

- First we Create Fee Categories Like Development Fee, Tutuion Fee, Transportation fee.
- Creating Fee Structure For Different Classes and it depends on siblings fee.
- Like If a Student has one sibling than Tution fees would be 50% discount, If there are two Siblings than Tution Fee would be 25%.
- Transportation Fee depends on various routes eg Bus Fee for Route1 : 500/- than Fee for Route2 : 400/-.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 29-Apr-2022**
<h3 align='center'>Implementing Fee on local server</h3>

- First we import data like Program, student, courses.
- Creating Fee category as per requirement Development Fee, Tution Fee, Transporatation Fee.
- Finding a way how to link siblings of same school using minimal customization.
- We set up students who have siblings but when we select option siblings studying in the same school then we are able to select students from available students but the program is not fetched.
- Along with this We find the received income cost center is also set in schedule. We can find all the income in the Fee cost center.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 30-Apr-2022**
<h3 align='center'>Try to optimize Notice.py Code</h3>

- As we use department for naming series so for this we have to change code when department and its abbrivation changed.
- To Remove this we add department abbrivation field in doctype.
- With following query abbr depends upon the department abbrivation also we haven't make changes in code also code become more simple than previous code. 
<br>

```py
department=self.department
abbr=frappe.db.get_value( 'Department' , department ,'department_abbreviation' )
self.name=make_autoname( 'NOTICE-' + abbr + '/' + '.YYYY.' + '/' + '.#####' )
```
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 2-May-2022**
<h3 align='center'>Creating Roles and permissions</h3>

- Creating Director Role and add permission for Viewing accounts, payroll, Employee details etc.
- Customize Deskview for Director Role.
- Creating Principal Role and add all academic views for Principal.
- Creating Instructor Role and allow all permissions needed to do their tasks.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 3-May-2022**
<h3 align='center'>Learn Different Salary component for Employee Salary</h3>

- Basic Pay of employee as per college pay scale.
- Add 5% Interim Relief in Basic pay.
- Adding Dearness allowance 142% in Basic Pay.
- Medical Allowance,CCA,PF(10%),HRA.
- These all are Earning in salary.
- Then we add Deduction component like PF(20%),Development tax, GI, SML, SMAF.
- By calculating all Earning & Deduction, we get Net Paid Amount. 
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 4-May-2022**
<h3 align='center'>Creating Salaries</h3>

- First we create salary component which are fixed these are declared in Salary Component.
- Next Create Salary Structure in which we group all Salary Component which are earning and deduction components.
- Setting up formula on Basic Pay like calculate IR(5%), ADA(142%) etc.
- After Successfully creating salary structure assigning it to employee where we define the Basic pay of Employee.
- At last in Salary Slip we select employee to whom we assign salary then salary structure automatically fetched and calculate base salary.    
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 5-May-2022**
<h3 align='center'>Creating Presentation with Other Team-mates in Reveal.JS</h3>

- Review all work which is done by us.
- Creating presentation add all Salary Components required.
- Add how Desk is visible for different Roles.
- What is visible to all student.
- Explaing other modules like Accounts, Assets, Payroll, Human Resource, Education Domain.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 6-May-2022**
<h3 align='center'>Working on Mentor-Mentee Task without erpnext</h3>

- Creating new database in which three tables Mentor, Mentee & Relation.
- Import data in these tables using csv files through terminal.
- Make connection of database with python file.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 7-May-2022**
<h3 align='center'>Install and use Flask</h3>

- As we need to show detail on webpage using jinja templating.
- After few searches we decide to use flask as a framework which render jinja template for html file.
- Again Make connection with database, but this time as adviced by teacher. we need to hide credential from public so that we push it on git.
- For hiding credentials we load details from another python file.
- Write basic hello world program and render it using jinja templating.
<br>


<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 9-May-2022**
<h3 align='center'>Showing detail in html file using jinja</h3>

- Creating a templates folder inside flask app where all the html files put together
- Make a funtion in which we put query select Mentor name from mentor table.
- Then render template with data and file name in which template is shown
```py
@app.route('/')
def example():
    cur.execute("SELECT Name FROM Mentor")
    data = cur.fetchall()
    return render_template('index.html', output = data)
```
- cur.execute is used for query and cur.fetchall() fetch all names from mentor table.
- And at the end funtion return render template in which filename, and assign data to output variable.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 10-May-2022**
<h3 align='center'>Showing Data on Webpage with Jinja and Bootstrap code</h3>

- Jinja template code for showing data on webpage. 
- In the below code under block content section we run a loop which fetch data from flask app.
- row[0] is used for show data without braces.
- jinja template code with Bootstrap

```jinja
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.0.0/dist/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">

    <title>Hello, world!</title>
  </head>
  <body>
    <div class="container">
    <table class="table">
      <thead class="thead-dark">
        <tr>
          <th scope="col">Mentor Name</th>
          <th scope="col">Mentee Name</th>
        </tr>
      </thead>
      <tbody>
        <tr rowspan="4">
          <td class="border">{{ mentor }}</td>          
          <td class="border">
          {% for row in output1 %}         
            {{ row[0] }}              
            <br>
          {% endfor %}
        </td>
        </tr>
        
        </tbody>
      </table>
    </div>

    <script src="https://code.jquery.com/jquery-3.2.1.slim.min.js" integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.12.9/dist/umd/popper.min.js" integrity="sha384-ApNbgh9B+Y1QKtv3Rn7W3mgPxhU9K/ScQsAP7hUibX39j7fakFPskvXusvfa0b4Q" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.0.0/dist/js/bootstrap.min.js" integrity="sha384-JZR6Spejh4U02d8jOt6vLEHfe/JQGiRRSQQxSfFWpi1MquVdAyjUar5+76PVCmYl" crossorigin="anonymous"></script>
  </body>
</html>
```
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 11-May-2022**
<h3 align='center'>Adding bus Fee in Fee doctype of erpNext</h3>

- By default we have Fee component in which all fee categories are fetched but as per our requirement we need to add bus fee which is different for each student.
- For which First we create two doctype one in which Route detail with Fees is stored and second is child doctype called Bus component which is fetched in Fee doctype.
- Then Apply changes in Bus component like fetch value from Route detail doctype.
- For calculating total bus component and fee component we have to write some code in fee.js file.

```js
calculate_total_amount: function(frm) {
	var grand_total0 = 0, grand_total1 = 0, grand_total = 0;

	for(var i=0;i<frm.doc.components.length;i++) {
		if( frm.doc.components[i].amount >= 0){
			grand_total0 += frm.doc.components[i].amount;
		}
		else{
			grand_total0 = 0;
		}
	}

	if(frm.doc.bus_components.length == 0)
	{
		grand_total1 = 0;
	}
	if(frm.doc.bus_components.length >= 1)
	{
	for(var i=0;i<frm.doc.bus_components.length;i++) {
		if( frm.doc.bus_components[i].amount > 0){
			grand_total1 += frm.doc.bus_components[i].amount;
		}
		else{
			grand_total1 = 0;
		}
	}
	}
	grand_total = grand_total0 + grand_total1;
	console.log(grand_total)
	frm.set_value("grand_total", grand_total);
}

frappe.ui.form.on("Bus Component", {
	amount: function(frm) {
		frm.trigger("calculate_total_amount");
	}
});
```
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 12-May-2022**
<h3 align='center'>Make changes for in fee files to save data at backend</h3>

- First write code in api.py file create whitelist() where we use condition if bus component available.
- Then use it in Javascript file as function where we call api.py and sending data field data to function.
- Now in fee.py we calculate the bus component in loop and send grand total in database throught which we succesfully generate receipt with correct calculations.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 13-May-2022**
<h3 align='center'>Understand the Salary Structure of different employees</h3>

- We are going to Accounts Department for understanding Salary structure of different employees.
- Understand their requirement related to salary like for different employee, there should be different grade pay.
- So they want they have customize option to add grade pay or not.
- They want also seprate record file for provident fund record of employees, provident fund loan record file.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 14-May-2022**
<h3 align='center'>Learning Salary Component for New Requirement</h3>

- First when we change our company from NSPS to GNDEC.
- Then all the Salary Components of employee are visisble in Salary Components but are not shown in Salary structure.
- After that we are finding some other solution so that we can use same structure in two companies. 
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 16-May-2022**
<h3 align='center'>Creating Salary Component</h3>

- According to new requirement different category employees have different components.
- Now same salary component can have different value for two employees like SML for accounts employee and teaching employee are different.
- We are creating all Salary Components without any value so that we can modifying it later in Salary Structure.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 17-May-2022**
<h3 align='center'>Creating Salary Structure</h3>

- After Creating all Salary components which are combined for all the employees.
- Now we are creating Salary Structure which is the combination of Salary Components in which we list all Earning and deduction components.
- In this we set formula that if basic pay is assigned to employee during the assignment of Salary Structure and Grade pay is added to employee when generating Salary Slip only then all the Earning and deduction components are calculated.
- The calculation is done when we save the salary slip in draft state after submit we can't modify it but in draft state we can made any changes at any time like adding or deleting components.
<br>
 
 


 









