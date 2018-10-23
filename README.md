# WordpressVSKali
Codepath Week 7: Project - Wordpress vs. Kali

Exploits Found:

1 - XSS vulnerability in plugin's Update-page
-> By adding script to the php of our plugin, we were able to exploit an XSS vulnerability within the update page of the plgugin tab.

Steps:

- Navigate to plugins page
- Go to the editor
- Add some script to the php
- Update the file
- Navigate to "Updates" tab under Dashboard

Tested Version: 4.2
Fixed Version: 4.7.1

<img src="https://github.com/amangarg1003/WordpressVSKali/blob/master/plugin-XSS.gif" width="800">


2 - XSS vulnerability in Page's Edit-page

-> By adding a script to the title of a page, we can exploit an XSS vulnerability. This script does not show up on the published blog page, but still triggers the alert.

Steps:

- Navigate to All Pages
- Select a page to edit
- Add some script to the end of page title
- Update the page
- Check the published website to see the script activate

Tested Version: 4.2
Fixed Version: 4.7.1

<img src="https://github.com/amangarg1003/WordpressVSKali/blob/master/edit_page-XSS.gif" width=800>


3 - XSS vulnerability in Post's Edit-page

-> By adding a script to the end of a post title, we are able to trigger that script as soon as we load the main page of the application.

Steps:

- Navigate to the Post tab
- Select a post to edit
- Add some script to the end of the post title
- Update the post
- Navigate to the main page

Tested Version: 4.2
Fixed Version: 4.2.5

<img src="https://github.com/amangarg1003/WordpressVSKali/blob/master/post_title-XSS.gif" width=800>

