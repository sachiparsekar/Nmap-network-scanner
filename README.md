Installation Instructions (Windows)

System Setup:

Operating System: Windows 10

Nmap Version: 7.95 

Terminal Used: Command Prompt (cmd.exe)/Powershell

Local IP Address: 192.168.154.1

Test Environment: Home network with internet access

Target IPs: Internal IP (192.168.154.1) and public host scanme.nmap.org

Tool Installation:

To install Nmap on Windows, follow these steps:

Step 1: Download the Installer

1.	Go to the official download page:
    https://nmap.org/download.html
2.	Under Microsoft Windows Binaries, click the link for the latest self-installer:
    Example: nmap-7.94-setup.exe (the version number may vary).
3.	Save the file to your system.

Step 2: Run the Installer

1.	Double-click the downloaded .exe file.
2.	Follow the on-screen instructions:
   a. Accept the license agreement.
   b. Keep the default components selected:
  	
  	Nmap command-line tool
  	
  	Zenmap GUI
  	
  	Npcap (essential for packet capture)
  	
3.	Click Install.
   
Note: Allow the installation of Npcap when prompted. It's required for many Nmap features.

Step 3: Verify Installation

After installation:

1.	Open Command Prompt (press Windows + R, type cmd, hit Enter).
2.	Type the following command:


Usage Instructions (Basic Commands)

1. Finding Live Hosts: 
Used to identify all devices currently connected to the subnet.
Useful in network auditing or before launching targeted scans.

2. Scanning a Safe Public Host: 
Verified Nmap's scanning capabilities on a known test server (scanme.nmap.org).
Ensures no unauthorized scanning on production or restricted systems.

3. Port Scanning: 
Helps discover potential open ports (e.g., 135, 139, 445, 902).
Can highlight services running on target machines, useful for threat assessment.

4. Aggressive Detection: 
Retrieves service versions, OS info, network distance, and running scripts (e.g., smb2-time, smb2-security-mode).
Suitable for deeper network reconnaissance and penetration testing.

5. Storing Output: 
Outputs are useful for documentation, security assessments, and reviewing results later.

-oN format provides clean, human-readable output
