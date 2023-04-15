# openports-scan
This program defines a function scan_ports that takes an IP address, a starting port number, and an ending port number as arguments. It then loops through all the ports in the range from the starting port to the ending port and attempts to establish a TCP connection to each one using the socket module. If the connection is successful, the port is considered open and its number is added to a list of open ports. Finally, the function returns the list of open ports.

To use this program, simply run it and follow the prompts to enter the IP address and port range to scan. The program will then print out a list of any open ports it finds on the specified IP address.
