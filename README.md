# yellowpages-task

# prerequisite
	- get ssl Certificate 
		 you can obtain a free certificate for your domain(s) from Let's Encrypt
		 
# database 
	database file is in root name as ads.sql
	create database named as ads then import the sql file 
	and change your mysql credintial in model/DB.php
	
# run project 
 - dowload project file 
 - unzip files in your htdocs file 
 - run the project like for guest http://localhost/yp_task
   for admin  http://localhost/yp_task/admin
 
 # layers
 	# front layer
		- display all advertisements on home page 
		- click on each ad description redirect to detail page of ads and it comments
		- you can add comment by loging in with facebook and and comment
		
	# backend layer
		-two types of admin manager , employee
		- manager had permission to add ,delete ,update ads and publish comments 
		- employee can add ,update comments only
		

	
