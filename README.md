# Bash_Script
The Port Scanner script is a simple Bash script designed to check the status of ports on a target IP address within a specified range. It helps identify whether a port is open or closed by attempting to establish a TCP connection. This tool is useful for network administrators and security professionals to quickly assess network configurations and troubleshoot issues.

Key Features:
Scans a specified port range on a target IP.
Reports each port as open or closed.
Uses a 1-second timeout for each port to avoid delays.

How It Works:
The script takes two inputs: a target IP address and a port range (e.g., 1-1000).
It attempts a TCP connection to each port and reports whether it is open or closed.
