# FIREWALL CONFIGURATION 

## Objective:
The objective of this task is to configure and test basic firewall rules to allow or block network traffic using Windows Defender Firewall.

## Tools Used:
- Windows Defender Firewall with Advanced Security
- Command Prompt (CMD)

## Methodology:

### 1. Opened Firewall Configuration Tool
Opened Windows Defender Firewall with Advanced Security to manage firewall settings and rules.

### 2. Viewed Existing Firewall Rules
Checked the current inbound firewall rules available on the system.

### 3. Created a Firewall Rule
Created a new inbound rule to block TCP Port 23 (Telnet).

**Rule Details:**
- Rule Name: Block Telnet Port 23
- Protocol: TCP
- Local Port: 23
- Action: Block
- Direction: Inbound

### 4. Verified the Rule
Verified that the firewall rule was successfully created and enabled using Command Prompt and the Firewall Management Console.

### 5. Confirmed Rule Application
Confirmed that the rule appeared in the Inbound Rules list and was actively blocking traffic on Port 23.

## Screenshots:

1. Windows Defender Firewall with Advanced Security
2. Inbound Rules List
3. Block Telnet Port 23 Rule
4. Command Prompt Verification

## Result:
Successfully configured and verified a firewall rule to block inbound traffic on TCP Port 23 (Telnet).

## Conclusion:
A firewall rule was successfully created, verified, and tested to block Telnet traffic on Port 23, improving the overall security of the system.
