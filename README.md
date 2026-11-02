# InformationGathering
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

## Pen Test Tools Categories:  

Following Categories of pen test tools are identified for information gathering:

Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network.
http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.

## OUTPUT:



## Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of facebook.com.
##output
<img width="812" height="757" alt="image" src="https://github.com/user-attachments/assets/2befcad3-54ee-40ef-a574-2a420f1ebadc" />



## Finding Hosting Company
get further detail by using ip2location.com website.
##output
<img width="1366" height="660" alt="image" src="https://github.com/user-attachments/assets/0ac6db0d-8ac5-47c4-acbe-0e08df373fe3" />



## History of the website:
## output
https://web.archive.org/

<img width="1366" height="661" alt="image" src="https://github.com/user-attachments/assets/174123ae-a9e3-4606-b8fa-2099b283c3a3" />

# Webserver Fingerprinting:

## Netcat:
```
sudo nc example.com 80
GET / HTTP/1.1
Host: example.com
```

##Output:
<img width="471" height="475" alt="image" src="https://github.com/user-attachments/assets/ad577294-b97c-46fa-87bc-a033b58ccb0c" />



## nmap:
###output
<img width="696" height="153" alt="image" src="https://github.com/user-attachments/assets/82b9ced1-2eb5-49b3-9541-41b05ecec0ab" />



## Whatweb
### output
<img width="800" height="500" alt="image" src="https://github.com/user-attachments/assets/57e4a3e8-0682-4e16-b935-3bb93fc379d3" />


## httprint
### output
<img width="453" height="501" alt="image" src="https://github.com/user-attachments/assets/c549e9df-ff04-4c2d-b8b1-0496380fa82e" />




# Tracing the Location
TCP Traceroute:
sudo traceroute -T www.google.com
## output
<img width="737" height="132" alt="image" src="https://github.com/user-attachments/assets/51cfe9ef-056f-4d07-9da9-cd33f3804dda" />

## UDP Traceroute:
sudo traceroute -U www.google.com
## output
<img width="536" height="230" alt="image" src="https://github.com/user-attachments/assets/939894da-f1da-4c91-bd37-5d05421918e8" />



## ICMP Traceroute:
sudo traceroute  www.google.com
## output
<img width="737" height="132" alt="image" src="https://github.com/user-attachments/assets/550a427b-b859-44a6-b87b-005c155810b7" />






## RESULT:
The information gathering techniques tools/procedure were  identified successfully
