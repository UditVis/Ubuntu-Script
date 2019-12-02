# Ubuntu-Script
Contains scripts for ubuntu. Startup script.

Steps to use startup script:
1) Login as sudo user using "sudo su -"
2) Go to "/etc/init.d" and create a file "startup-script" using vi or nano.
3) Copy template content from repo file - sample-script to your file "startup-script".
4) Modify as per requirements.
5) Exit vi editor, saving the changes.
6) Make file executable using, "sudo chmod +x <filename>", like "sudo chmod +x startup-script".
7) Update rc.d using, "update-rc.d <scriptname> defaults" and enter user and password.
8) Reboot to test.  
