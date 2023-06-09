# Boss-of-the-SOC-BOTS---Threat-Hunting-Using-Splunk
<br>

In today's rapidly evolving digital landscape, organizations face an increasing number of sophisticated cyber threats that can bypass traditional security defenses. To stay ahead of adversaries, proactive security measures such as threat hunting have become crucial. Splunk, a leading data analysis platform, offers powerful capabilities for threat hunting, enabling security teams/organisations to collect, analyse, and gain insights from vast amounts of machine-generated data to detect and mitigate potential risks before they escalate.
<br>

I took part in the Boss of the SOC BOTS, A CTF platform for information security professionals, researchers, students, and enthusiasts and i will be answering some questions from the dataset that's provided.
<br>
<br>

## Level 1: Finding Attack Servers
In this level we are going to answer the following questions:
1. Find the brand name of the vulnerability scanner.
2. Find the attacker's IP address.
3. Find the IP address of the web server serving "imreallynotbatman.com".
4. Find the name of the file used to deface the web server serving "imreallynotbatman.com".
5. Find the fully qualified domain name (FQDN) used by the staging server hosting the defacement file.
<br>
<br>

### Find the brand name of the vulnerability scanner.
![image](https://github.com/promisejeremiah/Boss-of-the-SOC-BOTS---Threat-Hunting-Using-Splunk/assets/48945500/fe833df4-d257-48b6-ba74-ed5aad356762)

<br>
<br>

### Find the attacker's IP address.
![image](https://github.com/promisejeremiah/Boss-of-the-SOC-BOTS---Threat-Hunting-Using-Splunk/assets/48945500/136f71a1-8f7c-40ed-b0a7-e336bce17a3e)

<br>
<br>

### Find the IP address of the web server serving "imreallynotbatman.com".
![image](https://github.com/promisejeremiah/Boss-of-the-SOC-BOTS---Threat-Hunting-Using-Splunk/assets/48945500/5a196e33-84f6-41c9-b627-8d06bcb0816d)

<br>
<br>

### Find the name of the file used to deface the web server serving "imreallynotbatman.com".
![image](https://github.com/promisejeremiah/Boss-of-the-SOC-BOTS---Threat-Hunting-Using-Splunk/assets/48945500/92e5938e-ac9c-4103-b05e-78d65fd45cc1)

<br>
<br>

### Find the fully qualified domain name (FQDN) used by the staging server hosting the defacement file.
![image](https://github.com/promisejeremiah/Boss-of-the-SOC-BOTS---Threat-Hunting-Using-Splunk/assets/48945500/f8211dc3-75e7-457b-a455-9caf68344326)

<br>
<br>

## Level 2: Identifying Threat Actors
In this level we are going to answer these questions:
1. Find the server's IP address that is hosting the staging server domain name.
2. Find the IP address performing a brute force attack against the server.
3. Find the name of the executable file the attacker uploaded to the server.

<br>
<br>

### Find the server's IP address that is hosting the staging server domain name.
![image](https://github.com/promisejeremiah/Boss-of-the-SOC-BOTS---Threat-Hunting-Using-Splunk/assets/48945500/597e4b1a-88f6-450b-951e-d62620c87f35)

<br>
<br>

### Find the IP address performing a brute force attack against the server.
![image](https://github.com/promisejeremiah/Boss-of-the-SOC-BOTS---Threat-Hunting-Using-Splunk/assets/48945500/4e7628e3-97b4-495f-ab31-1cc07203d2ec)

<br>
<br>

### Find the name of the executable file the attacker uploaded to the server.
![image](https://github.com/promisejeremiah/Boss-of-the-SOC-BOTS---Threat-Hunting-Using-Splunk/assets/48945500/6d102849-6e81-447e-81cf-27fa99eda9e0)

<br>
<br>

## Level 3: Using Sysmon and Stream
In this level we are going to answer the following questions:
1. Find that file's MD5 hash of the executable file the attackers uploaded to the server.
2. What was the first brute force password used?
3. What was the correct password found in the brute force attack?
4. How many seconds elapsed between the time the brute force password scan identified the correct password and the compromised login? Round to 2 decimal places.
5. How many unique passwords were attempted in the brute force attack?

<br>
<br>

### Find that file's MD5 hash of the executable file the attackers uploaded to the server.
![image](https://github.com/promisejeremiah/Boss-of-the-SOC-BOTS---Threat-Hunting-Using-Splunk/assets/48945500/d8660d68-5b55-4899-94d6-6dc92af266cb)

<br>
<br>

### What was the first brute force password used?
![image](https://github.com/promisejeremiah/Boss-of-the-SOC-BOTS---Threat-Hunting-Using-Splunk/assets/48945500/6aa6d341-9fc6-475a-86e5-b8934d8ddc40)

<br>
<br>

### What was the correct password found in the brute force attack?
![image](https://github.com/promisejeremiah/Boss-of-the-SOC-BOTS---Threat-Hunting-Using-Splunk/assets/48945500/3ce6cf61-b492-4d6e-a6d2-41c562478abd)

<br>
<br>

### How many seconds elapsed between the time the brute force password scan identified the correct password and the compromised login? Round to 2 decimal places.
![image](https://github.com/promisejeremiah/Boss-of-the-SOC-BOTS---Threat-Hunting-Using-Splunk/assets/48945500/f121d782-54d4-4c0c-a059-529e73da064a)

<br>
<br>

### How many unique passwords were attempted in the brute force attack?
![image](https://github.com/promisejeremiah/Boss-of-the-SOC-BOTS---Threat-Hunting-Using-Splunk/assets/48945500/3d9dedd0-e753-4ab4-8d58-d143c560828b)
