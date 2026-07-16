# Task 7 - Nmap Scan

## Objective
Perform a full TCP port scan on the Metasploitable 2 virtual machine using Nmap.

## Tool Used
- Nmap 7.99

## Command Used

```bash
nmap -p- -oN nmap-scan.txt 10.0.2.3
```

## Files Included
- nmap-scan.txt

## Result
A full TCP port scan was performed on the Metasploitable 2 VM. The scan identified multiple open services including FTP, SSH, Telnet, HTTP, SMB, MySQL, PostgreSQL, VNC, and IRC. The scan results were saved in normal text format and uploaded to this repository.
