## NAME: NAVEEN JAISANKER
## REG. NO.: 212224110039
## DATE: 30/08/2025

# Ex-02 InformationGathering
Information Gathering Techiques

# To perform information gathering techniques

# AIM:

To perform information gathering techniques using kali linux 

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:
Open terminal/browser and try execute necessary commands/use url to perform information gathering

## Architecture Diagram
```
                      +-------------------------+
                      |     Attacker System     |
                      |     (Kali Linux)        |
                      +-----------+-------------+
                                  |
                                  | Terminal / Browser
                                  | Executes Recon Tools
                                  v
      +------------------- Passive Recon --------------------+
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   WHOIS Query  | --> |    Domain Registrars    |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   DNS Enum     | --> |     Public DNS Servers  |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      +-----------------------------------------------------+

                                  |
                                  v

      +------------------ Active Recon ----------------------+
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   Nmap Scan    | --> |  Target Host/Network    |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  | WhatWeb, Wapp | --> |   Target Web Application |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  | theHarvester   | --> |     Search Engines      |  |
      |  +----------------+     +------------------------+  |
      +-----------------------------------------------------+

                                  |
                                  v
                    +-----------------------------+
                    |     Collected Information   |
                    | - IPs, Subdomains           |
                    | - Open Ports & Services     |
                    | - Technology Stack          |
                    | - Emails, Metadata          |
                    +-----------------------------+
```

## OUTPUT:
### Whois

<img width="1919" height="1033" alt="Screenshot 2025-08-30 151437" src="https://github.com/user-attachments/assets/14ec3bf5-99bb-4d62-b193-9ea1cbab948f" />


### Finding Hosting Company :
<img width="1919" height="1030" alt="Screenshot 2025-08-30 151457" src="https://github.com/user-attachments/assets/86db40e4-9d7b-4449-b497-12e72b9728ef" />

### History of the website :
<img width="1897" height="1031" alt="Screenshot 2025-08-30 151549" src="https://github.com/user-attachments/assets/0dfa6d15-8dcc-46b6-9d5d-d971704a13f5" />

### ping command :
<img width="747" height="310" alt="Screenshot 2025-08-30 153349" src="https://github.com/user-attachments/assets/8f85009b-54f0-4731-a6a0-f00d794be079" />

### whois :
<img width="959" height="1099" alt="Screenshot 2025-08-30 152005" src="https://github.com/user-attachments/assets/530cf653-1ee1-4998-974f-5ce3d3ffcf2a" />

### netcat :
<img width="674" height="1061" alt="Screenshot 2025-08-30 152106" src="https://github.com/user-attachments/assets/d21fb871-282f-43d7-a342-677712026c65" />

### nmap :
<img width="1017" height="605" alt="Screenshot 2025-08-30 152508" src="https://github.com/user-attachments/assets/9d757615-33a0-4332-abf8-a284f348b5c2" />

### whatweb :
<img width="1910" height="181" alt="Screenshot 2025-08-30 152611" src="https://github.com/user-attachments/assets/5be3fc95-f4fe-48b2-9bcd-e16acb7cb8f0" />

### httprint :
<img width="886" height="873" alt="Screenshot 2025-08-30 152856" src="https://github.com/user-attachments/assets/9ee66bbc-98c2-4ec1-bdb1-837f89299826" />

### TCP traceroute :
<img width="930" height="405" alt="Screenshot 2025-08-30 152930" src="https://github.com/user-attachments/assets/c2c29e4c-694a-4f56-aff7-7c06e76664e4" />

### UDP traceroute :
<img width="938" height="595" alt="Screenshot 2025-08-30 153006" src="https://github.com/user-attachments/assets/8f7bb5ee-4659-463f-ae65-f03842829a37" />

## RESULT:

The information gathering techniques tools/procedure were identified successfully.
