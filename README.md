# Wiremap
Wiremap.py is a Python script that serves as a port scanning and packet sniffing tool. Developed using the Scapy library, Wiremap.py offers network administrators, security professionals, and penetration testers a convenient and efficient solution for assessing the security of their networks.

The script prompts the user to input a target IP address and a range of ports to scan. It performs port scanning by iterating through the specified range of ports and attempting to establish TCP connections to each port. If a connection is successful, indicating an open port, Wiremap.py logs the port number and halts the scanning process.

In addition to port scanning, Wiremap.py utilizes a separate thread to capture network packets transmitted to or from the target IP address. By leveraging Scapy's sniff function, the script intercepts and analyzes the network traffic associated with the specified IP address. This packet sniffing capability enables users to gain insights into network communication patterns, perform protocol-level analysis, and identify potential security vulnerabilities.

Wiremap.py incorporates user-friendly features to enhance the scanning experience. It displays a progress bar using the tqdm library, providing real-time updates on the scanning progress. This allows users to monitor the scan and estimate the remaining time.

The script handles user interruptions gracefully by capturing the KeyboardInterrupt exception, ensuring proper termination and cleanup of the program.

Wiremap.py is a versatile tool that contributes to network security and vulnerability assessment. Its ease of use, accurate scanning results, and detailed packet analysis make it an invaluable asset in identifying potential security risks and fortifying network defenses. As network security requirements evolve, Wiremap.py can be updated and expanded to incorporate additional scanning techniques, support more protocols, and offer advanced filtering capabilities to adapt to changing security landscapes.

Command: 
Linux
1. sudo python wiremap.py --help
2. sudo python wiremap.py -f <ip_address> -p <port>
  
Windows
Run Cmd as admin
1. python wiremap.py --help
2. python wiremap.py -f <ip_address> -p <port>
Note: Make sure that your wiremap file is in the same folder in which you'll be executing these commands.
  
  
 Image: 
  
 ![Screenshot at 2023-05-23 17-33-23](https://github.com/haritimaatri/wiremap/assets/80319081/544df997-5785-4907-96cd-1ca095af6fa0)

  
