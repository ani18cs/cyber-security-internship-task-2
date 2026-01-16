User Accounts & Privileges
•	Verified existing users using:
	cat /etc/passwd
•	Identified current user:
    whoami
•	Checked sudo privileges:
	sudo -l

File Permissions & Ownership
•	Viewed permissions:
	ls -l
•	Changed permissions using chmod:
	chmod 700 filename
	chmod 644 filename
•	Changed ownership using chown:
	sudo chown user:user filename

Root vs Normal User
•	Root user has full control
•	Normal users have restricted access

Firewall Configuration (UFW)
•	Enabled firewall:
	sudo ufw enable
•	Checked status:
	sudo ufw status
•	Allowed SSH (if required):
	sudo ufw allow ssh

Running Processes & Services
•	Listed running processes:
	ps aux
•	Viewed services:
	systemctl list-units --type=service

Disable Unnecessary Services
•	Identified unnecessary service Disabled it:
	sudo systemctl disable service_name
	sudo systemctl stop service_name
