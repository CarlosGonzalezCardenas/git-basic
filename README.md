# git-basic

# This document contains tips on how to use git commands on the command prompt 

1.- First of all we have to configure the username and the email which we're going to be using, change 'User Name' and 'usermail@mail.com':

	git config --global user.name "User Name"
	git config --global user.email "useremail@mail.com"

2.- Create an ssh key:

	ssh-keygen -t rsa
  
3.- A meesage will appear asking in which file to save the key, 'User' and 'filename' must be changed to the your username and name of the file respectively:
	
	C:\Users\User\.ssh\filename 

6.- Once the ssh key is generated upload it on the github 'settings' tab.

7.- To download or 'clone' the repository on your local disk copy the github code-dowload-ssh option and on the command prompt write:

	git clone git@github.com:Username/filename.git
