# Lab 5 – EC2 and Amazon RDS Integration

## Objective
To deploy a MySQL database on Amazon RDS and connect it with an EC2-hosted application.

## Architecture
User → EC2 Instance → Amazon RDS (MySQL)

## Steps Performed

1. Launched EC2 instance (Ubuntu)
2. Created Amazon RDS MySQL instance
3. Configured security group (Port 3306 open)
4. Connected EC2 to RDS using MySQL client
5. Created database: lab5db
6. Created table: students
7. Inserted sample records
8. Developed Flask app on EC2
9. Connected Flask app to RDS
10. Displayed student data on browser

## Database Connection Details

Host: database-1.csx2scmee41b.us-east-1.rds.amazonaws.com
Port: 3306  
Database: database-1

## Application Access

EC2 Public URL:
http://32.192.35.110:5000

## Result
The application successfully connects to Amazon RDS and displays data from the students table in the browser.
