attacks/baseline_recon.md

Reconnaissance Scan Results
--------------------------
Target IP: 192.168.195.130
Scan Type: TCP SYN Scan (nmap -sS)

Observations:
- Host is reachable
- No open TCP ports detected
- System exposes minimal attack surface

Security Insight:
- Closed ports reduce risk of remote exploitation
- Services will be selectively enabled for learning and testing


Before SSH:
- No open ports
- Minimal attack surface

After SSH Exposure:
- Port 22/tcp open
- Remote access enabled
- Increased risk of brute-force attacks


Technique: T1110 – Brute Force
Observed Evidence:
- Multiple failed SSH authentication attempts
- Same source IP




