# Project: Logs Analysis
This project is part of the Udacity Intro to Progamming Nanodegree Program, Back-End Development module. 

**by Sahdique Mohamed**

# Project Purpose
To generate a reporting tool for a newspaper site powered by [PostgreSQL datebase](https://www.postgresql.org).

The reporting tool will answers the following questions: 

1. What are the most popular three articles of all time?
2. Who are the most popular articles of all time?
3. On which days did more than 1% of requests lead to errors?

# Prerequisites
The following is used for this project:

1.[Python 3](https://www.python.org/downloads/)

2.[Vagrant](https://www.vagrantup.com/)

3.[VirtualBox](https://www.virtualbox.org/wiki/Download_Old_Builds_5_1)

4.[Newsdata.sql](https://d17h27t6h515a5.cloudfront.net/topher/2016/August/57b5f748_newsdata/newsdata.zip)

In order for the reporting tool to run, Vagrant and VirtualBox software needs to be installed on the system.

# Using the Reporting Tool 
1. Install Python, Vagrant and Vritual Box
2. Place logsanalysis.py into your /vagrant directory
3. Place newsdata.sql into your /vagrant directory 
4. Navigate to the /vagrant directory and input `vagrant up` to start the virtual machine
5. Run `vagrant ssh` to log into your virtual machine
7. Load the database by running `psql -d news -f newsdata.sql`
8. View the reporting tool by running `python logsanalysis.py`



