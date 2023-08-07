Hello Peer Reviewer,
1. Python 3.9 is no longer supported so I used the latest 3.11 for this project.
The pipfile and pipfile.lock reflect this change.

2. The crendentials for MySQL are:
user: admindjango
password: employee@123!

You can create this user using
CREATE USER 'admindjango'@'localhost' IDENTIFIED BY 'employee@123!';
against your instance of MySQL.

Alternatively you can update the settings.py DATABASES setting with your own
MySQL admin credentials.

Thanks much,
-Eric