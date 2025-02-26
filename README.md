# Splunk-SIEM-Home-Lab

Splunk Home Lab

## « Overview »
This home-lab focused on setting up Splunk SIEM and real-world use cases

![image](https://github.com/user-attachments/assets/83156f21-9f70-4bdc-8a13-177509153fbe)

## 📌 Project Overview 

**1. Splunk Enterprise installed on Windows 11**

**2. Splunk Universal Forwarder installed on Ubuntu VM**

**3. Logs are forwarded from Ubuntu to Splunk for analysis**

## Requirements
**Hardware**:
  Ubuntu Server 20.04.6 LTS 
  Windows 11 Machine

**Software**:
   [Splunk Enterprise]((https://www.splunk.com/en_us/download/splunk-enterprise.html)) 
   [Splunk Universal Forwarder]((https://www.splunk.com/en_us/download/universal-forwarder.html_))

## « Lab Diagram »

![image](https://github.com/user-attachments/assets/af02b670-74e9-4e35-b03c-4f165a4a2093)


## 1. Splunk web interface showing received logs: 
![image](https://github.com/user-attachments/assets/5ca7004c-715b-4e44-99ca-b105c9a05536)

## ⚙️ Setup & Configuration

**1️⃣ Splunk Enterprise (Windows 11) Installation**

Download and install Splunk Enterprise from Splunk Official Site.

Start Splunk and create an admin account.

**2️⃣ Splunk Universal Forwarder (Ubuntu) Setup**

• Download and install the Splunk Universal Forwarder.

• Configure inputs.conf and outputs.conf to send logs to Splunk Server.

sudo /opt/splunkforwarder/bin/splunk enable boot-start

sudo /opt/splunkforwarder/bin/splunk start








