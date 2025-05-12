# custom-kali-vm-vuln-reverse
This project delivers a custom-built Linux virtual machine specifically tailored for vulnerability assessment and reverse engineering tasks. The VM includes a curated set of essential security tools, streamlining the workflow for cybersecurity professionals, students, and enthusiasts.


Custom Linux-based Machine For Vulnerability Assessment & Reverse Engineering 

Group Number: 2
________________________________________
Project Description
This project delivers a custom-built Linux virtual machine specifically tailored for vulnerability assessment and reverse engineering tasks. The VM includes a curated set of essential security tools, streamlining the workflow for cybersecurity professionals, students, and enthusiasts.
The environment also features a built-in help script with a user-friendly menu that provides quick, in-terminal descriptions of each tool available on the machine. This ensures new users can easily familiarize themselves with the toolkit and its purpose.

Tools & Frameworks Included
The virtual machine comes pre-installed with the following tools:

Vulnerability Assessment Tools
•	Nmap
•	Nikto
•	Metasploit Framework
•	SQLMap
•	Nessus
•	OpenVAS

Reverse Engineering Tools
•	Radare2
•	Ghidra
•	GDB
•	Binwalk

Browser Utilities
•	Firefox with FoxyProxy extension (for Burp Suite integration)

Help Script Details
A dedicated help script is provided at:
/help/Tools_Description
To run the script:
Open a terminal, navigate to the /help directory and run 
 ./Tools_Description.

Menu Overview:
Welcome to the Tool Help Script!
Please select a tool to get help with:
1.	Nessus
2.	Burp Suite
3.	Nikto
4.	Metasploit
5.	Radare2
6.	Ghidra
7.	Nmap
8.	GDB
9.	Binwalk
10.	OpenVAS
11.	SQLMap
12.	Exit
You can select a number to view a brief description of the corresponding tool.


Machine Credentials

Username: project
Password: vareproject123



Project Source Files

As GitHub has a 100MB per file limit, the complete virtual machine .ova file has been uploaded to Google Drive.
Download Link: https://drive.google.com/file/d/1SBkQyK_CQ8fg22tcvK-WGFlYx4sDJhqN/view?usp=sharing



Instructions to Run the Project

1.	You will need to download the following three files:
a.	.mf (manifest file)
b.	.ovf (Open Virtualization Format file)
c.	disk1.vmdk (virtual disk file)
Ensure that all three files are saved in the same directory on your system.
2.	Import the .ovf file into your VirtualBox or VMware:
a.	Open your virtualization software.
b.	Choose the option to import an appliance or open a virtual machine.
c.	Select the downloaded .ovf file and follow the on-screen instructions to complete the import.

3.	Start the machine using the following credentials:
a.	Username: project
b	Password: vareproject123

4.	Open a terminal and navigate to /help.
5.	Run the Tools_Description script to view tool descriptions.
6.	Firefox is pre-configured with the FoxyProxy extension for Burp Suite operations.




