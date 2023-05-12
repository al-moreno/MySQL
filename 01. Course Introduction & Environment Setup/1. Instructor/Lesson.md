# SQL - Course Introduction & Environment Setup


## Table Of Contents
- [Introduction]
- [Installing MySQL Server and Workbench]
- [Setting up the Database]
- [Additinal Resources]
- [Citation of material used in this lesson]


## Introduction

The language we will be coding in is Sequel, an acronym for Structured Query Language. We will use Sequel to manipulate tables with our database server. MySQL Workbench is the user interface that we will utilize to code, and the shell is a command-line interface that we can use to interact with MySQL Server. 

These four components are distinct, so let's review them quickly: 
1. Sequel is the language
2. MySQL Workbench is the user interface
3. MySQL Shell is a command-line interface
4. MySQL Server

Having completed that quick breakdown, let's move on to the installations. 


## Installing MySQL Server and Workbench for Windows

Welcome back!

To download MySQL on your Windows device, simply navigate to the official MySQL website and access the [MySQL Installer for Windows](https://dev.mysql.com/downloads/installer/) page. From there, you can easily locate the appropriate 32 or 64-bit download option and begin the installation process with ease.

After completing the download, we can navigate to the downloads folder and locate the MySQL-installer-community-### file, where ### represents the latest version of the software. To initiate the installation process, simply double-click on the file. During the installation process, you may encounter a prompt to download the .Net Framework. It is essential to download the correct version from an official Microsoft link before proceeding with the installation. This will ensure a smooth installation process and help avoid any potential errors.

After successfully installing the .Net Framework, you can return to the MySQL installer. If all the prerequisites are fulfilled, the software should be installed effortlessly without any hitches.

Now that you have completed the installation process, feel free to follow the step-by-step instructions provided in the [How to Install MySQL on Windows](https://www.dataquest.io/blog/install-mysql-windows/) guide on our website.

Congratulations on completing the installation process! To continue, we highly recommend following the comprehensive guide on [How to Install MySQL on Windows](https://www.dataquest.io/blog/install-mysql-windows/). The guide provides detailed, step-by-step instructions to help you get started with MySQL and maximize its potential on your Windows device. 

## Installing MySQL Server and Workbench for Mac

For Mac users, installing MySQL Server and Workbench is a slightly different process compared to Windows. Unlike Windows, there is no bundled installer available for Mac, and you will need to install both MySQL Server and Workbench separately.

For the server, you can find it here: https://dev.mysql.com/downloads/mysql/

and for the workbench, you can find it here: https://dev.mysql.com/downloads/workbench/

The installation process for MySQL Server and Workbench on Mac should be similar to what we covered in the Windows classes, including setting up the password for the server during the installation process. However, it's important to note that you should install MySQL Server first, followed by MySQL Workbench.

Additionally, keep in mind that since this software doesn't come from the App Store, you may need to give additional permissions on your Mac during the installation process.

## How to start MySQL Server

To start your server follow instructions on the following resource [How to start, stop, and restart MySQL database server?](https://tableplus.com/blog/2018/10/how-to-start-stop-restart-mysql-server.html)


## Setting up the Database

In this week's lecture, we'll be setting up a secure and robust database that we will use throughout the course. We will be utilizing a sample database designed explicitly for teaching purposes, making it the perfect resource for mastering SQL fundamentals.

To get started, you can simply search for "secure database download" on Google, which will redirect you to the Dev MySQL website. From there, you can access the installation instructions and download the zip file containing the three SQL scripts we will be using.

Once you have downloaded and unzipped the file, you can leverage MySQL Workbench to open the schema by double-clicking on the "schema.sql" file. To connect to the server, you will be prompted to enter your password. Once connected, you can select everything by using the "Control" key, hit the lightning bolt to execute the code, and refresh the left-hand side to visualize the secure database structure.

The next step involves opening the "data.sql" file and repeating the process of selecting everything, hitting the lightning bolt, and refreshing the left-hand side to load the data into the secure database.

Now that we have established the database and loaded our data, we're all set to start exploring ho



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













