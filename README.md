# task-4-firewall
cybersecurity intern 
1. Open Firewall Configuration Tool
Opened Windows Defender Firewall with Advanced Security via wf.msc or Control Panel.

2. List Current Firewall Rules
Navigated to Inbound Rules section.

Verified existing rules (Telnet, SSH, HTTP, etc.).

3. Add/Modify Rule to Block Port 23 (Telnet)
Located the Telnet rule in the inbound list.

Action was set to Block.

Profile: All

Enabled: Yes

Screenshot Evidence:
→ firewall establishment.png shows the Telnet rule as "Blocked".

🧪 4. Test the Block Rule
Used Command Prompt:

bash
Copy
Edit
telnet 192.168.1.1 80
