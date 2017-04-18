---
layout: default
title:  "Welcome to Jekyll!"
date:   2016-02-12 17:50:00
categories: main
---

++ AWS DB
There are two different limits -- that of the DB (10GB), and that of the DB instance server storage (300GB). A DB server instance could quite easily host several DBs, or a DB and support files such as logs, dumps, and flat file backups. Please see the AWS documentation for full details.

Further information:
https://d0.awsstatic.com/whitepapers/rdbms-in-the-cloud-sql-server-on-aws.pdf
http://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/CHAP_SQLServer.html

++ Under what circumstances would I choose provisioned IOPS over standard storage when creating an RDS instance?
++ The AWS platform is certified PCI DSS Level 1 Certified.
++ How many copies of my data does RDS - Aurora store by default? -- 6
++ Reserved Instances : https://aws.amazon.com/rds/faqs/#reserved-instances
++ In RDS, what is the maximum value I can set for my backup retention period? -- 35
++ In RDS, changes to the backup window take effect -- Immediately
++ When I create a new security group, all outbound traffic is allowed by default. -- True
++ With new RDS Db instances, automated backups are enabled by default? -- True
++ Amazon RDS does not currently support increasing storage on an active ________ Db instance. -- MS SQL Server 
++ S3 has eventual consistency for which HTTP Methods? -- overwrite PUTS and DELETES
++ Which consistency model for PUTS of new objects does S3 offer? -- 
