# Task 4: Firewall Configuration – Cyber Security Internship

## 🎯 Objective
Configure and test basic firewall rules on Windows to understand how traffic is filtered and how to block/allow specific ports.

## 🛠️ Tool Used
- Windows Defender Firewall with Advanced Security

## ✅ Steps Performed

1. Opened **Windows Defender Firewall with Advanced Security** from Control Panel.
2. Navigated to **Inbound Rules** to view existing rules.
3. Created a new rule to **block inbound TCP traffic on port 23 (Telnet)**.
4. Verified the rule was applied by checking its presence in the list.
5. (Optional) Tested the block using Nmap to check port status.
6. Removed the test rule to restore the firewall to its original state.

## 🔐 Why Block Port 23?
Telnet (port 23) is unencrypted and vulnerable to interception and attacks. Blocking this port enhances security.

## 📸 Screenshots Included
- Inbound rules list
- Rule creation for port 23
- Port block verification
- Rule removal/disablement

## ✅ Outcome
Learned how to:
- View, create, and remove inbound firewall rules
- Understand the importance of port filtering
- Use firewall as a layer of defense in network security
