# Information Gathering
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

![exp2_1](https://github.com/Skanthasishanth/InformationGathering/assets/118298456/76e21c7b-59f6-46bd-a8e5-f700fb6eb7e3)

## Finding IP adress:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of saveetha.ac.in.
```
ping saveetha.ac.in
```
## Output:

![exp2_2](https://github.com/Skanthasishanth/InformationGathering/assets/118298456/222be039-45a4-4e09-a110-140e857be4f4)

## Finding Hosting Company:
get further detail by using ip2location.com website.

## Output:

![exp2_3](https://github.com/Skanthasishanth/InformationGathering/assets/118298456/5315d237-c060-4ab5-90d1-235a931dfa14)

## History of the wbsite:
## Output:

https://web.archive.org/

![exp2_4](https://github.com/Skanthasishanth/InformationGathering/assets/118298456/c7cf5204-ba99-4188-9cf1-de3655277b33)

## Web server Fingerprint:
## Netcat:
```
nc 172.17.52.118 80
```
## Output:

![exp2_5](https://github.com/Skanthasishanth/InformationGathering/assets/118298456/98d50ffa-ff69-4b7d-bb35-15ef42f97f33)

## nmap:
```
nmap -p 21 -sV --script=banner ftp.vim.org
```
## Output:

![exp2_6](https://github.com/Skanthasishanth/InformationGathering/assets/118298456/4e92e308-8894-4ed9-86ce-7eadbe408fdb)

## Whatweb:
```
whatweb infosys.com
```
```
whatweb zoho.com
```
```
whatweb -v -a 3 172.17.52.201
```
## Output:

![exp2_7](https://github.com/Skanthasishanth/InformationGathering/assets/118298456/d2095ce1-a730-4431-a88a-02a71ef41f51)

## httprint:
```
httprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more
```
## Output:

![exp2_8](https://github.com/Skanthasishanth/InformationGathering/assets/118298456/6ceb7b19-be7e-4fef-ae62-79a7a3dd0159)

## Tracing the Location:
## TCP Traceroute:
```
sudo traceroute -T www.saveetha.ac.in
```
## Output:

![exp2_9](https://github.com/Skanthasishanth/InformationGathering/assets/118298456/aaabe9f9-34b0-43ff-93e9-e41770c37336)

## UDP Traceroute:
```
sudo traceroute -U www.saveetha.ac.in
```
## Output:

![exp2_10](https://github.com/Skanthasishanth/InformationGathering/assets/118298456/a9b5f3a0-5133-4150-871c-415fd84384f4)

## ICMP Traceroute:
```
sudo traceroute  www.saveetha.ac.in
```
## Output:

![exp2_11](https://github.com/Skanthasishanth/InformationGathering/assets/118298456/c37c5cd1-311c-4076-a1c4-5d0a3513fe96)

## RESULT:
The information gathering techniques tools/procedure were  identified successfully
