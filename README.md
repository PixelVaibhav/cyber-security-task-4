# cyber-security-task-4
# Task 4: Setup and Use a Firewall on Windows

## Objective
Configure and test basic Windows Firewall rules to allow or block network traffic.

---

## Tools Used
- Windows Defender Firewall
- Telnet client
- Windows PowerShell / Command Prompt

---

## Steps Performed

1. **Viewed existing firewall rules**
   - Used Windows Defender Firewall with Advanced Security.
   - Navigated to Inbound Rules.

2. **Blocked inbound traffic on port 23 (Telnet)**
   - Created a new Inbound Rule:
     - Port: TCP 23
     - Action: Block the connection
     - Applied to: Domain, Private, Public
     - Rule Name: `Block Telnet Port 23`

3. **Tested the blocking rule**
   - Tried connecting via `telnet localhost 23` (connection failed as expected).

4. **Allowed SSH (port 22)**
   - Created a rule to
