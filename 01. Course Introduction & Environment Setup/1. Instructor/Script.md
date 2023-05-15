# SQL - Course Introduction & Environment Setup


## Table Of Contents
- [Introduction]
- [Installing MySQL Server and Workbench]
- [Setting up the Database]
- [Additinal Resources]
- [Citation of material used in this lesson]


## Introduction

Greetings, everyone, and a warm welcome to the "Sequel for Absolute Beginners" course.

First and foremost, I would like to express my sincere gratitude to all of you for enrolling in this course. Our aim is to equip you with the necessary skills to work with SQL or Sequel and enable you to manipulate data with better techniques.

Through this course, you will gain mastery in Sequel, which can help you land jobs in several fields such as data analytics, database management, and full-stack development, to name a few.

We hope that you will enjoy this course while developing your skills, and we look forward to assisting you in your growth.

Allow me to introduce myself; my name is Ana, and I have been an instructor and curriculum developer for over five years. My experience in the IT industry spans over two decades, covering various roles such as Network Engineering, Software Engineering, and Project Management.

Let's now move on to the installation of the software required for this course. We have provided a walkthrough for both Windows and Mac users, so please follow the one that suits your device. After the installation, we need to ensure that we have MySQL Server, MySQL Workbench, and MySQL Shell to start working on our projects.

To provide a quick explanation of why we need these components: the language we will be coding in is Sequel, an acronym for Structured Query Language. We will use Sequel to manipulate tables with our database server. MySQL Workbench is the user interface that we will utilize to code, and the shell is a command-line interface that we can use to interact with MySQL Server. These four components are distinct, so let's quickly recap: Sequel is the language, MySQL Workbench is the user interface, and MySQL Shell is a command-line interface that we can use instead of the Workbench to interact with the server.

Having completed that quick breakdown, let's move on to the installations. 



## Installing MySQL Server and Workbench for Windows

Welcome back!

Now, let's begin by installing the necessary software for our devices. MySQL is an open-source software, which means it is free to use. To download MySQL, we can simply Google [*MySQL Community Downloads*](https://dev.mysql.com/downloads/) and navigate to the [MySQL Installer for Windows](https://dev.mysql.com/downloads/installer/)
page. From there, we can scroll down to the MySQL Installer for Windows section and select the 32 or 64-bit download option based on our device.

Once the download is complete, we can open the downloads folder and double-click on the MySQL-installer-community-### file, where ### stands for the latest version of the software. As the installation process begins, you may receive a message prompting you to download the .Net Framework. If so, ensure that you download the required version from an official Microsoft link before continuing with the installation.

Once the .Net Framework is installed, return to the MySQL installer. If all the requirements are met, the software should install without any issues.

Now that you have completed the installation process, feel free to follow the step-by-step instructions provided in the [How to Install MySQL on Windows](https://www.dataquest.io/blog/install-mysql-windows/) guide on our website.



## Installing MySQL Server and Workbench for Mac

For Mac users, installing MySQL Server and Workbench is a slightly different process compared to Windows. Unlike Windows, there is no bundled installer available for Mac, and you will need to install both MySQL Server and Workbench separately.

For the server, you can find it here: https://dev.mysql.com/downloads/mysql/

and for the workbench, you can find it here: https://dev.mysql.com/downloads/workbench/

The installation process for MySQL Server and Workbench on Mac should be similar to what we covered in the Windows classes, including setting up the password for the server during the installation process. However, it's important to note that you should install MySQL Server first, followed by MySQL Workbench.

Additionally, keep in mind that since this software doesn't come from the App Store, you may need to give additional permissions on your Mac during the installation process.

## How to start MySQL Server
To start your server follow instructions on the following resource [How to start, stop, and restart MySQL database server?](https://tableplus.com/blog/2018/10/how-to-start-stop-restart-mysql-server.html)


## Setting up the Database

Welcome to The Complete SQL For Absolute Beginners Course! In this week's lecture, we'll be setting up a secure database that we'll use throughout the course. We'll be using a sample database that we can use with MySQL for teaching purposes.

To begin, you can simply go to Google and type "secure database download" to access the secure sample database from the Dev MySQL website. From there, you can navigate to the installation instructions and download the zip file containing the three SQL scripts that we'll be using.

Once you've downloaded and unzipped the file, you can use MySQL Workbench to open the schema by double-clicking on the "schema.sql" file. To connect to the server, you'll need to enter your password when prompted. Once you're connected, you can select everything with control, hit the lightning bolt to execute the code, and refresh the left-hand side to see the secure database structure.

Next, open the "data.sql" file and repeat the process of selecting everything with control, hitting the lightning bolt, and refreshing the left-hand side to load the data into the secure database.

Now that we have our database set up and our data loaded, we're ready to start learning how to manipulate the data using SQL. Remember, learning a little each day adds up, so make sure to schedule learning time to ensure your success in this course!



## Additinal Resources
* [Install MySQL Server on the Ubuntu operating system](https://docs.rackspace.com/support/how-to/install-mysql-server-on-the-ubuntu-operating-system/)
* [Installing MySQL Workbench in Mac OS 10 and Connecting with MySQL Server](https://www.ccs.neu.edu/home/kathleen/classes/cs3200/MySQLWorkbenchMAC10.pdf)
* [MySQL Community Downloads](https://dev.mysql.com/downloads/)
* [Installing MySQL Workbench in Mac OS 10 and Connecting with MySQL Server](https://www.ccs.neu.edu/home/kathleen/classes/cs3200/MySQLWorkbenchMAC10.pdf)
* [How to start, stop, and restart MySQL database server?](https://tableplus.com/blog/2018/10/how-to-start-stop-restart-mysql-server.html)
* [How to Install MySQL on Windows](https://www.dataquest.io/blog/install-mysql-windows/) 


## Citation of material used in this lesson
Silveira, Otávio Simões. “How to Install Mysql on Windows: A Simple Guide (2023).” Dataquest, 6 Mar. 2023, www.dataquest.io/blog/install-mysql-windows/. 

"How to Start, Stop, and Restart MySQL Server." TablePlus, 16 Oct. 2018, tableplus.com/blog/2018/10/how-to-start-stop-restart-mysql-server.html.













