# Solutions

In this challenge we want to use XSS vulnerabilities to change the password for the grinch's account

since this website is like a forum where you can post comment XSS vulnerabilities are a possibility

when changing our own password we get this link: `http://IP/settings?new_password=pass123`

we check wether the comments we make on the site execute HTML, ie we enter `<h1> yo yo ma` and we can see that it executes

we then comment the following: `<script>fetch('/settings?new_password=pass123');</script>` 

the script tag tells the browser we want to execute javascript

and the fetch tag tells the browser to make a network request to that URL, thus making every visitor change their password to **pass123**

if you check the network tab in inspect you can see that the request is being made everytime you refresh the page
