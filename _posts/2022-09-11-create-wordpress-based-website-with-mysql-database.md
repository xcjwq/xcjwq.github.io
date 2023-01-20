---
layout: post
title: Create Wordpress Based Website with MySQL Database
date: 2022-09-11
categories: ["3rd Semester", "Database Security"]
img_path: https:///github.com/wyebit/wyebit.github.io/tree/main/_posts/media/2022-09-11-create-wordpress-based-website-with-mysql-database/
---

## Prerequisites:
- Windows OS
- [XAMPP](https://www.apachefriends.org/download.html)
- [Wordpress package](https://wordpress.org/download/)
- Some good internet connection

## Here we go:
1.	Download XAMPP on the website, and adjust the version into the one you prefer  
![1](1.png)
2.	Install and follow the settings by default (next till the end)  
![2](2.png)
3.	Finished the installation (don’t check the box for start the control panel), get a restart for your machine, so XAMPP will have fresh start next (actually, restarting is not that necessary, but why not?)  
![3](3.png)
4.	Upon booting up, search for XAMPP and ALWAYS run it as administrator to let it work properly  
![4](4.png)
5.	Start two services that we need it for later, those are Apache and MySQL  
![5](5.png)
6.	Download wordpress package and extract the package then move the folder to htdocs of XAMPP  
![6](6.png)
7.	Restart Apache’s service  
![7](7.png)
8.	Open a browser, and type: localhost/wordpress, then the introductory will begin  
![8](8.png)
9.	Fill the database credentials and else  
![9](9.png)
10. If you encountering database problem e.g., database not found; create a new database on localhost/phpmyadmin with the same credential you used when running setup from wordpress  
![10](10.png)  
![10-2](10-2.png)
11. Run the setup, type the username and else  
![11](11.png)
12. Finish the setup  
![12](12.png)
13. Run the web by accessing: localhost/wordpress  
![13](13.png)
14. And if you want further costumization, go for: localhost/wordpress/wp-admin, then you can continue  
![14](14.png)
15. Voila!:clap: