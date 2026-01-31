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
<img width="1918" height="1074" alt="Screenshot 2026-01-30 092910" src="https://github.com/user-attachments/assets/d1af6d80-d6c7-4fa3-aefe-7c485b473e13" />



## Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of makemytrip.com
##output
<img width="1016" height="371" alt="Screenshot 2026-01-30 094551" src="https://github.com/user-attachments/assets/dbd151b5-6552-4ac0-8405-26e00361eaef" />



## Finding Hosting Company
get further detail by using ip2location.com website.
##output
<img width="1900" height="1038" alt="Screenshot 2026-01-31 131111" src="https://github.com/user-attachments/assets/4d63f1a9-9897-4eee-9d01-bafc251de304" />

 
## ip2location
<img width="1918" height="1037" alt="Screenshot 2026-01-30 094157" src="https://github.com/user-attachments/assets/83f66d46-bfd9-45a5-9caa-6fcb1df08d85" />




# Webserver Fingerprinting:

## Netcat:
sudo nc example.com 80
GET / HTTP/1.1
Host: example.com
<img width="380" height="307" alt="image" src="https://github.com/user-attachments/assets/15a5d3d6-693c-494d-9352-d0863ae9bed5" />




## nmap:
###output
<img width="615" height="240" alt="Screenshot 2026-01-30 094712" src="https://github.com/user-attachments/assets/b8d74a51-989c-4f29-aa52-86ecb21174ed" />



## Whatweb
### output
<img width="1919" height="191" alt="Screenshot 2026-01-31 130341" src="https://github.com/user-attachments/assets/1a0ffc86-6419-4783-b23f-337ad6c3fd8a" />


# Tracing the Location
TCP Traceroute:
sudo traceroute -T makemytrip.com
## output
<img width="714" height="127" alt="Screenshot 2026-01-31 130556" src="https://github.com/user-attachments/assets/40c0ad5d-3013-43d3-bf9d-3d6ac3dd965e" />



## UDP Traceroute:
sudo traceroute -U makemytrip.com
## output
<img width="617" height="409" alt="Screenshot 2026-01-31 130717" src="https://github.com/user-attachments/assets/b0b845d3-2edc-44cf-a9ac-c6dda620a4c2" />



## ICMP Traceroute:
sudo traceroute  makemytrip.com
## output
<img width="646" height="363" alt="Screenshot 2026-01-31 130916" src="https://github.com/user-attachments/assets/fa44c8c1-a1d1-436a-98dc-39c1ec1ac08d" />






## RESULT:
The information gathering techniques tools/procedure were  identified successfully
