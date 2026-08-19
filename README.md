# CLOUD-DATA-STORAGE-SERVER
CLOUD DATA STORAGE SERVER

```
NAME: DHARSHINI S N
REG NO: 212224230062
```
## AIM
To create and configure an Amazon RDS MySQL DB instance with Multi-AZ deployment, connect it to a web application using a security group and DB subnet group, and perform CRUD (Create, Read, Update, Delete) operations on the database through the application.

## ALGORITHM
1.Log in to the AWS Management Console.

2.Create a DB Security Group allowing MySQL (3306) access from the Web Security Group.

3.Create a DB Subnet Group with subnets in two Availability Zones.

4.Launch an Amazon RDS MySQL Multi-AZ DB instance.

5.Configure the DB instance with the required username, password, and database name. Wait until the database status becomes Available and copy the endpoint.

6.Open the provided web application using the Web Server IP.

7.Enter the RDS endpoint, database name, username, and password.

8.Connect the application to the database.

9.Test the application by adding, editing, viewing, and deleting records.

***Output***

<img width="1892" height="812" alt="Screenshot 2026-08-07 191926" src="https://github.com/user-attachments/assets/55f3288c-de21-46a2-8445-abd538b8e039" />

<img width="1900" height="788" alt="Screenshot 2026-08-07 191951" src="https://github.com/user-attachments/assets/e6a7bb65-a0ff-431e-98ae-3e58b39760f1" />

<img width="1907" height="732" alt="Screenshot 2026-08-07 192338" src="https://github.com/user-attachments/assets/fca6a610-007c-4b92-b879-b66868fc055a" />

<img width="1897" height="748" alt="Screenshot 2026-08-07 194127" src="https://github.com/user-attachments/assets/18a8881a-f15d-4d48-bf7e-f32db976f60b" />




***RESULT***
Successfully created and configured an Amazon RDS MySQL Multi-AZ database, connected it to the web application, and performed database operations (insert, update, delete, and retrieve records) successfully.

