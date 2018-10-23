# WordpressVSKali
Codepath Week 7: Project - Wordpress vs. Kali

Exploits Found:

1 - XSS vulnerability in plugin's update-page
-> By adding script to the php of our plugin, we were able to exploit an XSS vulnerability within the update page of the plgugin tab.

Steps:

- Navigate to plugins page
- Go to the editor
- Add some script to the php
- Update the file
- Navigate to "Updates" tab under Dashboard

<img src="https://github.com/amangarg1003/WordpressVSKali/blob/master/plugin-XSS.gif" width="800">
