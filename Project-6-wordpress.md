# WEB SOLUTION WITH WORDPRESS
In this project we are tasked to prepare storage infrastructure on two Linux servers and implement a basic web solution using WordPress. WordPress is a free and open-source content management system written in PHP and paired with **MySQL** or **MariaDB** as its backend Relational Database Management System (RDBMS).

The Project 6 consists of two parts:

1. Configure storage subsystem for Web and Database servers based on Linux OS. The focus of this part is to give you practical experience of working with disks, partitions and volumes in Linux.

2. Install WordPress and connect it to a remote MySQL database server. This part of the project will solidify your skills of deploying **Web and DB** tiers of Web solution.
As a DevOps engineer, your deep understanding of core components of web solutions and ability to troubleshoot them will play essential role in your further progress and development.

Three-tier Architecture
Generally, **web**, or **mobile** solutions are implemented based on what is called the Three-tier Architecture.

## Three-tier Architecture is a client-server software architecture pattern that comprise of 3 separate layers.

1. Presentation Layer (PL): This is the user interface such as the client server or browser on your laptop.
2. Business Layer (BL): This is the backend program that implements business logic. Application or Webserver
3. Data Access or Management Layer (DAL): This is the layer for computer data storage and data access. Database Server or File System Server such as FTP server, or NFS Server

In this project, you will have the hands-on experience that showcases Three-tier Architecture while also ensuring that the disks used to store files on the Linux servers are adequately partitioned and managed through programs such as **gdisk and LVM** respectively.

## 3-Tier Setup
1. A Laptop or PC to serve as a client
2. An EC2 Linux Server as a web server (This is where you will install WordPress)
3. An EC2 Linux server as a database (DB) server

## RedHat OS was adopt for this project

## Step 1       
— Prepare a Web Server

1. An EC2 instance was launch that served as “Web Server”. Three (3) volumes created in the same availability zone AZ as the Web Server EC2 each of 10 GiB.

2. All three volumes attached to the Web Server EC2 instance one by one.

3. The **lsblk command** was used to inspect what block devices are attached to the server. Notice names of your newly created devices. All devices in Linux reside in **/dev/ directory**. Inspect it with ls /dev/ and make THe 3 newly created block devices names are xvdf, xvdg and xvdh as presented.

![lsblk](./Images/sudo-lsblk)










> *The documentation can be modify later to effect changes*

| Name | Description | Date |
|:---  |    :----:   |  ---:| 
|Olaolu| Pro-6 Wordpress & Database  |28-10-23| 

*Thank you*
