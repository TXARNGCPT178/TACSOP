# Tasks related to the Linux OS
At the start of a Vulnerability Assessment or Cyber Incident Response you will want to follow a process of Enumeration, Monitoring, and Hardening. This section outlines helpful processes and commands to assist with the VA lifecycle.

## Enumeration

#### Services and Ports

Use `netstat` to view running serices and list listening ports. Determine their applicability on the host.

`netstat -tulpn`

Print the status of any task

`service <service name> status`

Print the status of the apache (http) service:

`service httpd status`

Display running processes:

`ps auxf`

Display top running processes/CPU %:

`top`

#### Users & Connections

Display logged in users:

`w`

Display last logged in users:

`last`

To kill a user session. Look up their corresponding shell process ID:

`ps t`

Issue a `kill -9 PID`:

`kill -9 30737`


## Hardening
