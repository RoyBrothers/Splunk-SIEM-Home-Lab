# Splunk-SIEM-Home-Lab

Splunk Home Lab

« Overview »
This home-lab focused on setting up Splunk SIEM and real-world use cases

![image](https://github.com/user-attachments/assets/83156f21-9f70-4bdc-8a13-177509153fbe)

Requirements
Hardware:
  Ubuntu Server 22.04(for Splunk Enterprise)
  Windows 11 Machine

Software:
  Splunk Enterprise)
  Splunk Universal Forwarder

« Lab Diagram »

![image](https://github.com/user-attachments/assets/af02b670-74e9-4e35-b03c-4f165a4a2093)


</> Setting up Splunk SIEM on Ubuntu Server

• Install Splunk Enterprise software on Ubuntu server

• Install Splunk Security Essentials App

• Import BOTS V2 Dataset


🧑‍💻Excercises- Investigating Web-based attacks

• SQL Injection: Analyze web logs to detect potential SQL injection attempts.(Hint: Look for unusual characters or SQL keywords used in URI parameters, such as ' or 1=1.)
• Cross-Site Scripting (XSS): Monitor web logs for signs of Cross-Site Scripting (XSS) attacks.(Hint: Search for requests containing suspicious JavaScript keywords like "script", "<script>", or "onload".)
• Cross-Site Request Forgery: Identify potential Cross-Site Request Forgery (CSRF) attacks in web logs.(Hint: Look for requests with unexpected or unauthorized actions, such as changes in user settings or profile information.)
• Directory Traversal: Search for indications of Directory Traversal attacks in web logs.(Hint: Check for requests containing "../" or "%2e%2e/" sequences in the URI, attempting to access files outside the web root.)
• Brute Force: Monitor access logs for patterns indicative of brute force attacks.(Hint: Look for repeated login attempts from the same IP address or requests with multiple failed authentication attempts.)
• Session Hijacking: Detect potential session hijacking attempts by analyzing web logs.(Hint: Look for multiple logins from different IP addresses for the same user account in a short time frame.)
• Remote Code Execution: Identify potential Remote Code Execution (RCE) attempts in web logs.(Hint: Look for requests with unusual file extensions or commands that may indicate attempts to execute arbitrary code on the server.)
• XXL External Entity: Search for indications of XML External Entity (XXE) attacks in web logs.(Hint: Look for requests with XML payloads containing references to external entities or unusual XML processing instructions.)
• Insecure Deserialization Detection: Detect potential Insecure Deserialization attempts in web logs.(Hint: Look for requests with serialized data or references to known serialization libraries vulnerable to exploitation.)
• SSRF Detection: Monitor web logs for signs of Server-Side Request Forgery (SSRF) attacks.(Hint: Look for requests with URLs pointing to internal or sensitive resources, or containing unexpected protocols like "file://" or "gopher://".)


🧑‍💻Excercises- Investigating Network-based attacks

• Port Scanning: Detect port scanning activities in network logs.(Hint: Look for a large number of connection attempts from the same source IP to different destination ports within a short time frame.)
• DDoS Attack: Identify Distributed Denial of Service (DDoS) attacks in network logs.(Hint: Watch for a sudden increase in traffic volume or a high number of connection requests to a single destination IP or port from multiple source IPs.)
• Brute Force SSH Attack: Detect brute force SSH login attempts in authentication logs.(Hint: Check for repeated failed login attempts from the same source IP address within a short time frame.)
• DNS Tunneling: Identify DNS tunneling activities in DNS logs.(Hint: Look for DNS queries with abnormally large query sizes, which may indicate DNS tunneling attempts to exfiltrate data.)
• Malicious Payload: Detect known malicious payloads in network logs using Suricata IDS or Zeek IDS.(Hint: Search for network logs containing signatures or indicators associated with known malware or exploit kits.)
• Malicious File Download: Detect malicious file downloads in HTTP server logs.(Hint: Search for HTTP requests with file extensions commonly associated with malware, such as ".exe" or ".dll".)
• Network Reconnaissance: Identify network reconnaissance activities in network logs using Suricata IDS.(Hint: Look for network logs containing events indicative of port scanning activities, such as multiple connection attempts from the same source IP to different destination IPs.)
• Man-in-the-Middle (MitM) Attack: Detect potential Man-in-the-Middle (MitM) attacks in network logs.(Hint: Look for network logs indicating rejected connections or SYN packets without completing the TCP handshake, which may suggest ARP spoofing or MitM attacks.)
• Data Exfiltration: Identify data exfiltration attempts in network logs.(Hint: Look for network logs containing large outbound data transfers or unusually high volumes of data transmitted from internal to external destinations, which may indicate data exfiltration attempts.)

