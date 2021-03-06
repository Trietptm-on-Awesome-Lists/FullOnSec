## These could be usefull for information gathering 

### [Censys.io](https://censys.io/)
- Use: 443.https.tls.certificate.parsed.extensions.subject_alt_name.dns_names:target.com. Where 'target.com' = the website you want to scan

#### [CloudFlair](https://github.com/christophetd/CloudFlair)
- A tool that scans for origin servers behind Cloudflare to reveal the true IP. Makes use of the Censys API to use internet-wide scans and looks for similarities in web content. 

### [Shodan.io](https://shodan.io)
- Search engine for the internet of things 

### [Crt.sh](https://crt.sh/)
- Scan websites for an insight on certificates with this tool .

### [Whois](https://whois.domaintools.com/)
- Learn more about the network, (sub)domains and DNS

### [Certstream](https://certstream.calidog.io/)
-  A free service and simple library for getting data from the Certificate Transparency Log (CTL) network in real time

### [Netcraft](https://www.netcraft.com/)
- Used for webserver identification and collecting available (sub)domains

### [MXtoolbox](http://mxtoolbox.com/)
- Another tool which could help with the recon phase, has all the functionality above tools have 

### [DNSdumpster](https://dnsdumpster.com/)
- DNS recon & research, find & lookup DNS records

### nslookup
- Name Server lookup
```
nslookup -type=MX example.com
```

### Dig
- Same functionality as nslookup
```
dig *.example.com +short
```

### Nmap
- Used for network scanning and discovery
```
nmap -p 80 -sV -sS -O ta.rg.et.IP
```
Send ICMP requests and TCP scans on port 80 and 443 of the target: 
``` 
nmap -sn ta.rg.e.t 
```

### Hping3
- Packet generator. One of the de facto tools for security auditing and testing of firewalls and networks
```
hping3 -c 100 -p 445 -S target.com \ or ta.rg.et.IP
```

### Netcat 
- Great network tool for port listening and establishing a connection to the webserver, scanning, transferring files and can be used as a backdoor
```
nc mail.server.net 25
```

### [Whatweb](https://github.com/urbanadventurer/WhatWeb)
- Identifying a website from SQL errors to which CMS is used etc. Kali has this installed by default
```
whatweb -v www.target.com 
```
### cURL
- curl is a tool to transfer data from or to a server
```
curl --head target.com 
```

### Bucket Finder
- https://digi.ninja/projects/bucket_finder.php

### Ports with tools
- https://github.com/nixawk/pentest-wiki/blob/master/3.Exploitation-Tools/Network-Exploitation/ports_number.md

### AXFR  
- https://github.com/UnaPibaGeek/ctfr

### Tool for scanning open S3 buckets and dumping the contents 
- https://github.com/sa7mon/S3Scanner 

### Tool for checking subdomains that are vulnerable for takeover 
- https://takeover.cyberint.com/ 

### Search engine for exploits
- https://sploitus.com/
