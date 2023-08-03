# MySQL-User-Manual
## Concept 
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

<table>
<tr><th> Table For Books Id </th><th> Table For Author's Id </th></tr>
<tr><td>

| Book's ID | Book's Name | Author's Name |
|---|---|---|
| 1 | A Thousand Splendid Suns | 2 |
| 2 | 1984 | 3 |
| 3 | Start With Why | 1 |


| Author's ID | Author's Name | Books |
|---|---|---|---|
| 1 | Simon Sinek | 3, 25 |
| 2 | Khaled Hosseini | 1, 45, 46 |
| 3 | George Orwell | 2, 10 |

</td></tr>
</table>
 
 