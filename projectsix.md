# WEB SOLUTION WITH WORDPRESS 

## In this project we will prepare storage infrastructure on two Linux servers and implement a basic web solution using WordPress.

WordPress is a free and open-source content management system written in PHP and paired with MySQL or MariaDB as its backend Relational Database Management System (RDBMS).

The Project will consist of two parts:

1. Configure storage subsystem for Web and Database servers based on Linux OS. 
2. Install WordPress and connect it to a remote MySQL database server. 

### Three-tier Architecture
Generally, web, or mobile solutions are implemented based on what is called the Three-tier Architecture.

**Three-tier Architecture** is a client-server software architecture pattern that comprise of 3 separate layers.

![like so](./images/six.jpg)

1. **Presentation Layer (PL):** This is the user interface such as the client server or browser on your laptop.
2. **Business Layer (BL):** This is the backend program that implements business logic. Application or Webserver
3. **Data Access or Management Layer (DAL):** This is the layer for computer data storage and data access. Database Server or File System Server such as FTP server, or NFS Server

#### In this project, we will showcase Three-tier Architecture while also ensuring that the disks used to store files on the Linux servers are adequately partitioned and managed through programs such as gdisk and LVM respectively.

### Our 3-Tier Setup
1. A Laptop or PC to serve as a client
2. An EC2 Linux Server as a web server (This is where we will install WordPress)
3. An EC2 Linux server as a database (DB) server

### *We will be using **RedHat** OS for this project*

