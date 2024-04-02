# Information Gathering
Information Gathering Techniques

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

![op1](https://github.com/Skanthasishanth/InformationGathering/assets/118298456/e18f9ec3-6b90-4937-a8f5-2cf597e7cf05)

## Finding IP adress:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of saveetha.ac.in.
```
ping saveetha.ac.in
```
## Output:

![op2](https://github.com/Skanthasishanth/InformationGathering/assets/118298456/c79eb70c-ded6-470d-bdf6-61e4540a1854)

## Finding Hosting Company:
get further detail by using ip2location.com website.

## Output:

![op3](https://github.com/Skanthasishanth/InformationGathering/assets/118298456/228c43c6-3e90-48e6-92f2-72817a496c89)


## History of the website:
## Output:

https://web.archive.org/

![op4](https://github.com/Skanthasishanth/InformationGathering/assets/118298456/a7c46119-0854-4703-b120-48d21e273e6b)

## nmap:
```
nmap saveetha.ac.in
```
## Output:

![op5](https://github.com/Skanthasishanth/InformationGathering/assets/118298456/616c53a3-43c2-476a-b893-fc89eaa8bd40)

## Whatweb:
```
whatweb -v -a 3 saveetha.ac.in
```
```
whatweb infosys.com
```
```
whatweb zoho.com
```
## Output:

![op6a](https://github.com/Skanthasishanth/InformationGathering/assets/118298456/72765969-04e0-4bbc-b81c-126e28cfcd3c)

![op6b](https://github.com/Skanthasishanth/InformationGathering/assets/118298456/cfd8f9fe-5e8b-4d7c-a524-ee0c95b25592)

## httprint:
```
httprint -h 103.21.58.21 -s /usr/share/httprint/signatures.txt -P0 |more
```
## Output:

![exp_httprint](https://github.com/Skanthasishanth/InformationGathering/assets/118298456/c725ff45-4226-4434-98b8-9e0e09e29170)

## Tracing the Location:
## TCP Traceroute:
```
sudo traceroute -T www.saveetha.ac.in
```
## Output:

![op7](https://github.com/Skanthasishanth/InformationGathering/assets/118298456/66e47c03-a560-4e94-b29d-cd447384dc00)

## UDP Traceroute:
```
sudo traceroute -U www.saveetha.ac.in
```
## Output:

![op8](https://github.com/Skanthasishanth/InformationGathering/assets/118298456/0d44c29e-3edb-4ba3-9ccd-18bd87283090)

## ICMP Traceroute:
```
sudo traceroute  www.saveetha.ac.in
```
## Output:

![op9](https://github.com/Skanthasishanth/InformationGathering/assets/118298456/c878d9ba-35ca-4106-9360-d768379d74af)

## RESULT:
The information gathering techniques tools/procedure were identified successfully
