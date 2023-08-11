# MySQL-User-Manual

## Concept 

### Summary 
Structured Query Language (SQL) is a standardized tool for communicating with relational 
databases like MySQL, Microsoft SQL Server, and Oracle. It originated in the 1970s to manage 
data in IBM's system database and was formalized by 1986. In SQL databases, data is organized 
into tables with columns representing attributes and rows for individual records identified 
by a unique PRIMARY KEY. Relationships between data points are established using FOREIGN KEYS. 
For example, Book and Author IDs create a one-to-many relationship, enhancing data organization 
and reducing duplication. SQL not only manipulates data but also enables joining data based on 
embedded relationships.

### Detailed Overview
Structured Query Language is a standard language for communicating with relational 
database management systems. There are different databases like MySQL, Microsoft SQL 
Server, Oracle all of which are based on SQL with their little variations. It was 
initially developed in the early 70’s to mutate and retrieve data from IBM’s system 
database and by 1986 it was standardized into syntax that remains extremely popular 
in technical applications. 

Today a relational database organizes data into tables kind of like an Excel spreadsheet 
where columns contain attributes or types of data while each row represents an 
individual record or data point with its own unique id known as PRIMARY KEY we 
can establish relationships between data points by taking the unique id from one row 
and storing it on different row in a different table in a special column known as a 
FOREIGN KEY.

 | Book's ID | Book's Name | Author's Name |
 ---|---|---
 | 1 | A Thousand Splendid Suns | 2 |
 | 2 | 1984 | 3 |
 | 3 | Start With Why | 1 |
 
 | Author's ID | Author's Name |  Books |
 ---|---|---
 | 1 | Simon Sinek | 3, 25 |
 | 2 | Khaled Hosseini| 1, 45, 46 |
 | 3 | George Orwell | 2, 10 |
 
Here, in the above example, you can see how Book's ID and Author's ID are used as PRIMARY KEY 
and FOREIGN KEY. What this tables shows us that each book have one author, but one author can
write multiple books. What we have done here is structured our data in its smallest normal form
to eliminate duplication and redundancy. Now, the role of SQL is not not only to read, create,
update, and delete data but also to join data together based on the relationships embedded within
it. 

## How To Download, Install And Configure MySQL On Windows

### Summary
Download MySQL Installer: Visit the official MySQL website, navigate to the Downloads section, 
and choose the MySQL Installer for Windows. Download the installer executable.
Run Installer: Double-click the downloaded installer executable to run it.
### Prerequisite
CPU: Intel Core or Xeon 3GHz (or Dual Core 2GHz) or equal AMD CPU. 
Cores: Single (Dual/Quad Core is recommended) RAM: 4 GB (6 GB recommended) 
Graphic Accelerators: nVidia or ATI with support of OpenGL 1.5 or higher.
### Steps
1. Open your web browser and visit [Microsoft SQL Server Downloads link](https://www.microsoft.com/en-in/sql-server/sql-server-downloads) 
2. Download the version of SQL server that best suits your requirements.
3. Once download is complete, start the installation by either double-clicking the downloaded 
package icon or by right clicking and selecting "INSTALL". 
4. Proceed through the installation process, accepting all prompts, and click "NEXT" to begin 
installation.
5. After the installation is completed, click on "FINISH".
6. A new window will appear after clicking "FINISH". Keep clicking on NEXT, unless you want
to change the to change the installation drive (e.g., from drive C) or port (e.g., Port 3306). 
Otherwise, proceed by clicking "NEXT." 
7. You'll be prompted to set a password. Set your password and remember it. This password
will be required to access MYSQL command prompt. 
8. After entering password and clicking "NEXT", click on "EXCUTE".
9. Click on "FINISH" when window displays "CONFIGURATION FILE CREATED. WINDOWS SERVICE MYSQL 
INSTALLED".
### Result
* Go to your device's search bar and type "MySQL," then select "MYSQL COMMAND LINE."
* Enter the password you set earlier.
* MySQL is now successfully installed and configured on your system.