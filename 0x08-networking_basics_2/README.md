0x08. Networking basics #1

Learning Objectives
At the end of this project, you are expected to be able to explain to anyone, without the help of Google:
What is localhost/127.0.0.1
What is 0.0.0.0
What is /etc/hosts
How to display your machine’s active network interfaces

TASKS
    0. Change your home IP
Write a Bash script that configures an Ubuntu server with the below requirements.

Requirements:

localhost resolves to 127.0.0.2
facebook.com resolves to 8.8.8.8.
The checker is running on Docker, so make sure to read this

    1. Show attached IPs
Write a Bash script that displays all active IPv4 IPs on the machine it’s executed on.
Obviously, the IPs displayed may be different depending on which machine you are running the script on.

Note that we can see our localhost IP :)

   2. Port listening on localhost
Write a Bash script that listens on port 98 on localhost.

Terminal 0

Starting my script.

sylvain@ubuntu$ sudo ./100-port_listening_on_localhost
Terminal 1

Connecting to localhost on port 98 using telnet and typing some text.