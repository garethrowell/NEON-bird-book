# 01 Introduction to PostgreSQL 

SQL is one of the big three data science coding 
languages, along with R and Python. While R provides libraries 
for data visualization and statistical analysis, and Python serves 
as a general programming language, along with its own graphics, 
mathematics, and machine learning libraries, SQL lives within
the confines of relational databases where it gives the coder 
strict control over massive quantities of data. Unlike R and 
Python, SQL operates with logical statements applied to sets 
of data. 
Learning SQL and the basics of relational databases gives
data scientists the opportunity to deal with very large and complex datasets 
while still maintaining control over data quality throughout the workflow.

There are many different alternative software platforms for working with SQL. 
In this brief guide, we will focus on PostgreSQL, which is the most comprehensive open source SQL database platform 
available. 
For the project described here, I will use the core database functionality which is just a 
fraction of the total features available in PostgreSQL. 
In addition, we'll be looking at plpgsql, the procedural scripting language that
comes with PostgreSQL.

Where to start? Binaries for Windows, Mac, and Linux are available at the main PostgreSQl 
website https://www.postgresql.org. Additional
binaries for Unix and Linux-like operating systems may also be available in distro specific repositories. 
All versions of PostgreSQL come with a terminal shell command line interface called psql. I'll be using
the psql shell environment for most of the coding. That, along with a text editor of your choice, is 
sufficient to develop all the SQL dataabase features needed for our analyitcs. Finally, I will also be using Python
to pull data using APIs and for some data visualizations once the core database work is running. Data
APIs and visualizations could just as easiily be completed using R tidyverse and R ggplot or other data
science tools.










