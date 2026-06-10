# Nmap-Cheat-Sheet-
Quick reference guide for common Nmap commands and scanning techniques.

**Basic Usage**
  Purpose                       Command
Scan a host                nmap 192.168.1.1
Scan a domain              nmap scanme.nmap.org
Multiple targets           nmap 192.168.1.1 192.168.1.2
Subnet scan                nmap 192.168.1.0/24


**Port Scanning**
    Purpose               Command
Specific ports       nmap -p 80,443 target
Port range           nmap -p 1-1000 target
All ports            nmap -p- target
Top 100 ports        nmap --top-ports 100 target

