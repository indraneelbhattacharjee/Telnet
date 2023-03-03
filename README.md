# Telnet

The code connects to a remote device using Telnet and sends login credentials.
It then sends a command to the device to display information about its interfaces and retrieves the output of the command.
Finally, the code prints the output and closes the Telnet connection.
Note that Telnet is an insecure protocol, as login credentials and other sensitive data are transmitted in plain text.
It's recommended to use more secure protocols like SSH or HTTPS instead, especially for remote access to network devices.
