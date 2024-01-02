# Lesson - User Management

Command 	                                Description 	
sudo adduser username 	        To add a new user
sudo passwd -l 'username' 	To change the password of a user
sudo userdel -r 'username' 	To remove a newly created user

To add a user to a group
sudo usermod -a -G GROUPNAME USERNAME 

To remove a user from a group
sudo deluser USER GROUPNAME

Shows information of all the users logged in
finger
 	 
Gives information of a particular user                                 
finger username 	                   
