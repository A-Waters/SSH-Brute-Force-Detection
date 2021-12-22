# Brute force SSH detector

Designed for debian, this script uses bash scripting to determine whether or not a ssh brute force attack is happening to the device. It dose this by monitoring the /var/log/auth.log file for failed logins. If there is a large amount of failed logins the script will notify the user

## how to use
simply download the file 'sshd_brute_force' and run the file as root.

    sudo ./sshd_brute_force

