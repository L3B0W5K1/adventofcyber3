# Soultions 

## What is the name of the folder for the admin dashboard?

to enumerate the folders for the website we use dirbuster with the following command: `dirb <IP>` 

dirbuster will use a pre-installed wordlist called **common.txt** with the most common folders for a website

after some tries we get the **/admin** folder

## In your web browser, try some default credentials on the newly discovered login form for the "administrator" user. What is the password?

heading to the folder we get a login page

the most common passwords for administrator are:
- administrator (commonly preconfigured and unchanged password)
- password123
- letmein

and password **administrator** worked this time

