# Enumeration
Enumeration Techniques

# Explore Google hacking and enumeration 

# AIM:

To use Google for gathering information and perform enumeration of targets

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various Google hacking keywords and enumeration tools as follows:


### Step 3:
Open terminal and try execute some kali linux commands

## Pen Test Tools Categories:  

Following Categories of pen test tools are identified:
Information Gathering.

Google Hacking:

Google hacking, also known as Google dorking, is a technique that involves using advanced operators to perform targeted searches on Google. These operators can be used to search for specific types of information, such as sensitive data that may have been inadvertently exposed on the web. Here are some advanced operators that can be used for Google hacking:

site: This operator allows you to search for pages that are within a specific website or domain. For example, "site:example.com" would search for pages that are on the example.com domain.
Following searches for all the sites that is in the domain yahoo.com
## Output:
<img src="https://github.com/user-attachments/assets/3496cff3-c6ae-4a37-b238-4bbef8288f4f" width=600>


filetype: This operator allows you to search for files of a specific type. For example, "filetype:pdf" would search for all PDF files.
Following searches for pdf file in the domain yahoo.com
## Output:
<img src="https://github.com/user-attachments/assets/c29cedf0-03f2-4add-804e-1c4d75ead34d" width=600>

intext: This operator allows you to search for pages that contain specific text within the body of the page. For example, "intext:password" would search for pages that contain the word "password" within the body of the page.
## Output:
<img src="https://github.com/user-attachments/assets/2bea9ec7-0bd9-4b5e-84fc-53a01439da9a" width=600>

inurl: This operator allows you to search for pages that contain specific text within the URL. For example, "inurl:admin" would search for pages that contain the word "admin" within the URL.
## Output:
<img src="https://github.com/user-attachments/assets/4068b7c6-1ce4-48f8-9972-35bf7f45857c" width=600>

intitle: This operator allows you to search for pages that contain specific text within the title tag. For example, "intitle:index of" would search for pages that contain "index of" within the title tag.
## Output:
<img src="https://github.com/user-attachments/assets/a8f936b3-52ba-4efc-879c-69da88ab157f" width=600>

link: This operator allows you to search for pages that link to a specific URL. For example, "link:example.com" would search for pages that link to the example.com domain.
## Output:
<img src="https://github.com/user-attachments/assets/a9df044c-752f-409b-a107-048e267adbd8" width=600>

cache: This operator allows you to view the cached version of a page. For example, "cache:example.com" would show the cached version of the example.com website.
## Output:
<img src="https://github.com/user-attachments/assets/62ea14b1-8286-4a46-bcab-0e122394afc0" width=600>
 
## DNS Enumeration
### DNS Recon
provides the ability to perform:
Check all NS records for zone transfers
Enumerate general DNS records for a given domain (MX, SOA, NS, A, AAAA, SPF , TXT)
Perform common SRV Record Enumeration
Top level domain expansion
## Output:
<img src="https://github.com/user-attachments/assets/6c454a8b-ee75-4d4d-9bc8-95c58c3492dd" width=600>

### dnsenum
Dnsenum is a multithreaded perl script to enumerate DNS information of a domain and to discover non-contiguous ip blocks. The main purpose of Dnsenum is to gather as much information as possible about a domain. The program currently performs the following operations:

Get the host’s addresses (A record).
Get the namservers (threaded).
Get the MX record (threaded).
Perform axfr queries on nameservers and get BIND versions(threaded).
Get extra names and subdomains via google scraping (google query = “allinurl: -www site:domain”).
Brute force subdomains from file, can also perform recursion on subdomain that have NS records (all threaded).
Calculate C class domain network ranges and perform whois queries on them (threaded).
Perform reverse lookups on netranges (C class or/and whois netranges) (threaded).
Write to domain_ips.txt file ip-blocks.
This program is useful for pentesters, ethical hackers and forensics experts. It also can be used for security tests.
## Output:
<img src="https://github.com/user-attachments/assets/9ca3f22d-123b-4514-a826-44bd250767f3" width=600>

## smtp-user-enum
Username guessing tool primarily for use against the default Solaris SMTP service. Can use either EXPN, VRFY or RCPT TO.
<img src="https://github.com/user-attachments/assets/bd8b7165-6090-4815-8067-46cb75fa6951" width=600>

In metasploit list all the usernames using head /etc/passwd or cat /etc/passwd:

select any username in the first column of the above file and check the same


## Telnet for smtp enumeration
Telnet allows to connect to remote host based on the port no. For smtp port no is 25
telnet <host address> 25 to connect
and issue appropriate commands
  
## Output
<img src="https://github.com/user-attachments/assets/6c7e722b-22c1-4376-8904-41acd74c68f8" width=600>  

## nmap –script smtp-enum-users.nse <hostname>

The smtp-enum-users.nse script attempts to enumerate the users on a SMTP server by issuing the VRFY, EXPN or RCPT TO commands. The goal of this script is to discover all the user accounts in the remote system.
## Output:
<img src="https://github.com/user-attachments/assets/76712d38-d29c-4f42-a4d6-e700192457df" width=600>


## RESULT:
The Google hacking keywords and enumeration tools were identified and executed successfully

