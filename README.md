Port Scanner is simple network scanner designed to identify open ports on a specified target IP address. The tool iterates through all ports in the range of 1 to 65535 and attempts to establish a connection to each port using nc (netcat). If a connection is successful, the tool then tries to identify the service associated with the open port based on common well-known ports.
For each identified open port, the tool provides a brief description of the service along with the service name. 

**Installation **

Download the folder or sudo git clone https://github.com/GIRISH05/Network-Scanner.gicd Network-Scanner 
cd Network-Scanner 
chmod +x PortScanner 
./PortScanner <target.ip>
