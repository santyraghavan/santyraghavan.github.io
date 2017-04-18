---
layout: default
title:  "Welcome to Jekyll!"
date:   2016-02-12 17:50:00
categories: main
---

<h2> AWS DB </h2>

There are two different limits -- that of the DB (10GB), and that of the DB instance server storage (300GB). A DB server instance could quite easily host several DBs, or a DB and support files such as logs, dumps, and flat file backups. Please see the AWS documentation for full details.
https://d0.awsstatic.com/whitepapers/rdbms-in-the-cloud-sql-server-on-aws.pdf
http://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/CHAP_SQLServer.html

<li>Under what circumstances would I choose provisioned IOPS over standard storage when creating an RDS instance?
<li>The AWS platform is certified PCI DSS Level 1 Certified.
<li>How many copies of my data does RDS - Aurora store by default? -- 6
<li>Reserved Instances : https://aws.amazon.com/rds/faqs/#reserved-instances
<li>In RDS, what is the maximum value I can set for my backup retention period? -- 35
<li>In RDS, changes to the backup window take effect -- Immediately
<li>When I create a new security group, all outbound traffic is allowed by default. -- True
<li>With new RDS Db instances, automated backups are enabled by default? -- True
<li>Amazon RDS does not currently support increasing storage on an active ________ Db instance. -- MS SQL Server 
<li>S3 has eventual consistency for which HTTP Methods? -- overwrite PUTS and DELETES
<li>Which consistency model for PUTS of new objects does S3 offer? -- 
