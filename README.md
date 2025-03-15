# AWS-HandsOn-Notes
Mastering AWS through the Ajira AWS re/Start Program, featuring projects, notes, and practical labs."
AWS Learning Journey 🚀
Welcome to my AWS Learning Journey repository! 🌟 This is where I document everything I learn during the Ajira AWS re/Start Program. From core AWS concepts to hands-on projects, this repo will serve as my knowledge hub as I explore the exciting world of cloud computing.
___

# "Week One:Introduction to Cloud Computing
Cloud computing is the delivery of various computing services (like servers, storage, databases, networking, software, and more) over the internet. It allows for on-demand access to computing resources without the need for managing physical hardware2..

## Basic Computing Concepts
- Computer: An electronic device that processes data. 
    
- Hardware: Physical components of a computer (e.g., CPU, RAM, storage).

- Software: Programs and operating systems that run on hardware.

- Data vs. Information: Data is raw, unorganized facts; information is processed data that is meaningful.

## Advantages of Cloud Computing

- Cost Savings: Reduces the need for physical hardware and maintenance.

- Scalability: Easily scales resources up or down based on demand.

- Flexibility: Access resources from anywhere with an internet connection.

- Disaster Recovery: Provides backup and recovery solutions.

- Speed: Quick deployment of services and applications.

## AWS (Amazon Web Services)
AWS is a comprehensive cloud computing platform offering a wide range of services, including computing power, storage, and databases.

## AWS Pricing
AWS uses a pay-as-you-go model, meaning you only pay for what you use. There are various pricing options, including On-Demand, Savings Plans, Reserved Instances, and Spot Instances6.

## AWS S3 (Simple Storage Service)
AWS S3 is an object storage service that offers scalability, data availability, security, and performance. It's used for storing and managing data for various applications7.

## AWS Service Categories
- AWS offers services across several categories, including:

- Compute: Services like EC2, Lambda, and Elastic Beanstalk.

- Storage: Services like S3, EBS, and Glacier.

- Database: Services like RDS, DynamoDB, and Redshift.

- Networking: Services like VPC, Route 53, and Direct Connect.

- Security: Services like IAM, Cognito, and Shield.

## AWS Elastic Compute (EC2)
Amazon EC2 provides resizable compute capacity in the cloud. It allows users to run virtual servers and scale up or down as needed6.

## Introduction to Amazon EC2
Amazon EC2 offers a variety of instance types optimized for different use cases. It supports various pricing models, including On-Demand, Savings Plans, Reserved Instances, and Spot Instances6.

---
# Week Two: Linux


## Introduction to Amazon Linux
Amazon Linux is a Linux distribution provided by Amazon Web Services (AWS). It's optimized for performance and security on AWS infrastructure, designed to provide a stable, secure, and high-performance execution environment for applications running on Amazon EC2.

## Linux Command Line
The Linux command line, accessed via a terminal, allows users to interact with the system through text-based commands. Common commands include:

'''
> ls: List directory contents

> cd: Change directory

> pwd: Print working directory

> cp, mv, rm: Copy, move, and remove files

> cat, less, grep: Display and search file content

'''

## Linux Users and Groups
Linux is a multi-user system, with each user having a unique user ID. Groups help manage permissions for multiple users. Common commands:

> useradd, usermod, userdel: Add, modify, delete users

> groupadd, groupmod, groupdel: Manage groups

> chmod, chown: Change file permissions and ownership

## Editing Files in Linux
Editing files in Linux can be done using text editors like vi, nano, and gedit. Basic commands for vi:

> i: Enter insert mode

> Esc: Exit insert mode

> :w: Save changes

> :q: Quit

> :wq: Save and quit

## Working with Linux Files
Managing files includes tasks like creating, copying, moving, and deleting files. Useful commands:

> touch: Create an empty file

> mkdir: Create a directory

> cp, mv, rm: Copy, move, remove files and directories

> find: Search for files

## Managing File Permissions
File permissions determine who can read, write, or execute a file. Command examples:

> ls -l: Display file permissions

> chmod: Change file permissions (e.g., chmod 755 file)

> chown: Change file owner (e.g., chown user:group file)

## Managing Linux Processes
Processes are instances of running programs. Useful commands:

> ps: Display active processes

> top, htop: Real-time process monitoring

> kill: Terminate a process (e.g., kill 1234)

> bg, fg: Manage background and foreground processes

## Managing Linux Services
Services are background processes managed by the system. Commands to manage services:

> systemctl start/stop/restart service: Control services

> systemctl enable/disable service: Enable or disable service at boot

> systemctl status service: Check service status

## The Bash Shell
Bash (Bourne Again SHell) is a popular command-line interpreter for Unix/Linux systems. It allows users to execute commands, create scripts, and automate tasks.

## Bash Shell Scripting
Bash scripting involves writing scripts to automate tasks. Basics:

- Shebang (#!/bin/bash): Specifies the script interpreter

Variables: variable=value

- Control Structures: if, for, while

Functions: Define reusable code blocks

## Linux Software Management
Managing software involves installing, updating, and removing packages. Tools vary by distribution:

> apt, dpkg: Debian-based systems (e.g., Ubuntu)

> yum, rpm: Red Hat-based systems (e.g., CentOS)

> zypper: SUSE systems

## Managing Log Files
Log files store system and application event records. Tools for managing logs:

> journalctl: View systemd logs

> /var/log/: Directory containing log files

> tail, less, grep: View and search logs

---

# Week Three: Networking

## Introduction to Networking
Networking refers to the practice of connecting computers and other devices to share resources and information. It enables communication between devices and can be as simple as two computers connected with a cable or as complex as the internet.

## Networking Concepts
Network: A group of interconnected devices that can communicate with each other.

- LAN (Local Area Network): A network that covers a small geographic area, like a home or office.

- WAN (Wide Area Network): A network that covers a large geographic area, such as a city, country, or even globally.

## Protocols: Rules and conventions for communication between network devices (e.g., TCP/IP, HTTP).

## Internet Protocol (IP)
The Internet Protocol (IP) is a set of rules for routing and addressing packets of data so they can travel across networks and reach the correct destination. IP addresses are unique numerical labels assigned to each device on a network.

## Networking in the AWS Cloud
 -AWS provides a suite of networking services to help build and manage cloud networks:

- VPC (Virtual Private Cloud): Isolated cloud resources for secure network configuration.

- Route 53: Scalable DNS web service.

Direct Connect: Dedicated network connection to AWS.

## IP Subnetting
Subnetting divides a large network into smaller, more manageable sub-networks (subnets). Each subnet has a unique range of IP addresses. This enhances security and improves network performance by reducing broadcast traffic.

## Additional Networking Protocols
- TCP (Transmission Control Protocol): Ensures reliable data transfer between devices.

- UDP (User Datagram Protocol): Allows faster, but less reliable data transfer.

- HTTP/HTTPS: Protocols for accessing and transmitting web pages securely.

- FTP (File Transfer Protocol): Used for transferring files between devices.

## Additional Networking Technologies
- VPN (Virtual Private Network): Creates a secure, encrypted connection over a less secure network, such as the internet.

- Firewalls: Security systems that control incoming and outgoing network traffic based on predetermined security rules.

- Load Balancers: Distribute network or application traffic across multiple servers to ensure reliability and performance
---

# Week 4: Security
### **Security Summary Notes**  

## **Introduction to Security**  
Security refers to the protection of systems, networks, and data from cyber threats. It involves policies, technologies, and best practices to safeguard information from unauthorized access, modification, or destruction.


## **Security Life Cycle & Prevention**  
- **Identify**: Recognizing assets and vulnerabilities.  
- **Protect**: Implementing security controls to reduce risks.  
- **Detect**: Monitoring and identifying potential threats.  
- **Respond**: Taking action against security incidents.  
- **Recover**: Restoring operations after an incident.  

## **Network Hardening**  
- Disabling unnecessary ports/services.  
- Using firewalls and intrusion detection systems (IDS).  
- Enforcing encryption for data in transit.  
- Implementing Virtual Private Networks (VPNs).  

## **System Hardening**  
- Regularly updating and patching software.  
- Removing unnecessary applications and users.  
- Implementing strong authentication mechanisms.  
- Enforcing the principle of least privilege (PoLP).  

## **Data Security**  
- Encrypting data at rest and in transit.  
- Implementing access control policies.  
- Using data loss prevention (DLP) solutions.  
- Backing up data regularly and securely.  

## **Public Key Infrastructure (PKI)**  
- A framework for managing digital certificates and encryption keys.  
- Components: Certificate Authority (CA), Registration Authority (RA), and Key Management.  
- Enables secure communication via SSL/TLS.  

## *Amazon Certificate Manager (ACM) Demonstration**  
- AWS service for provisioning, managing, and deploying SSL/TLS certificates.  
- Automates certificate renewals and integrations with AWS services.  

## **Identity Management**  
- Managing user access and authentication.  
- Ensuring users have the right level of access to systems.  
- Enforcing Multi-Factor Authentication (MFA).  

## **AWS Identity and Access Management (IAM)**  
- Controls access to AWS resources.  
- Key Components: Users, Groups, Roles, Policies.  
- Supports Role-Based Access Control (RBAC) and MFA.  

## **Detection**  
- Monitoring systems for suspicious activities.  
- Using automated threat detection tools.  

## **AWS CloudTrail**  
- Tracks API calls and user activities in AWS.  
- Logs actions for auditing and security investigations.  

## **AWS Config**  
- Monitors and records AWS resource configurations.  
- Helps ensure compliance with security policies.  

## **Response**  
- Incident response plans for addressing security breaches.  
- Automating responses with AWS Lambda or AWS Security Hub.  

## **Analysis**  
- Performing security audits and threat analysis.  
- Using AWS tools like GuardDuty for threat detection.  

## **Security Best Practices**  
- Enforce the principle of least privilege (PoLP).  
- Regularly audit permissions and access logs.  
- Encrypt all sensitive data.  
- Implement continuous monitoring.  

## **AWS Compliance Programs**  
- Ensures AWS meets industry regulations (ISO, HIPAA, GDPR).  
- AWS Artifact provides compliance reports.
- 
## **AWS Security Resources**  
- **AWS Well-Architected Framework** – Security guidelines.  
- **AWS Security Hub** – Centralized security insights.  
- **AWS Trusted Advisor** – Security recommendations.  
- **AWS Shield** – DDoS protection. 


# Week 5: 📌 Python Programming Cheat Sheet  

## 🐍 Python Basics  
- Interpreted, dynamically typed, high-level language.  
- **Variables:**  
  ```python
  x = 10  
  name = "Python"  
  ```
- **Data Types:** `int`, `float`, `str`, `bool`, `list`, `tuple`, `dict`, `set`  
- **I/O Operations:**  
  ```python
  name = input("Enter name: ")  
  print(f"Hello, {name}!")  
  ```
- **Operators:** `+`, `-`, `*`, `/`, `%`, `//`, `**`, `and`, `or`, `not`  

## 🔁 Python Flow Control  
- **Conditional Statements:**  
  ```python
  if x > 0:  
      print("Positive")  
  elif x == 0:  
      print("Zero")  
  else:  
      print("Negative")  
  ```  
- **Loops:**  
  ```python
  for x in range(5):  
      print(x)  

  x = 0  
  while x < 5:  
      print(x)  
      x += 1  
  ```  

## 🛠️ Functions in Python  
- **Defining a function:**  
  ```python
  def greet(name):  
      return f"Hello, {name}!"  

  print(greet("TechTinker"))  
  ```  
- **Lambda Functions:**  
  ```python
  square = lambda x: x**2  
  print(square(5))  
  ```  

## 📦 Modules & Libraries  
- **Importing Modules:**  
  ```python
  import math  
  from datetime import datetime  
  ```
- **Popular Libraries:** `numpy`, `pandas`, `requests`, `flask`, `django`  
- **Creating a Module:** Save functions in a `.py` file and import them using `import module_name`  

## 🖥️ System Administration with Python  
- **Execute Shell Commands:**  
  ```python
  import os  
  os.system("ls")  # Linux/Mac  
  os.system("dir") # Windows  
  ```
- **File Handling:**  
  ```python
  with open("file.txt", "r") as file:  
      content = file.read()  
      print(content)  
  ```  

## 🐞 Debugging & Testing  
- **Print Debugging:**  
  ```python
  print(var)  
  ```
- **Using `pdb`:**  
  ```python
  import pdb; pdb.set_trace()  
  ```
- **Unit Testing:**  
  ```python
  import unittest  

  class TestMath(unittest.TestCase):  
      def test_add(self):  
          self.assertEqual(1 + 1, 2)  
  ```  

## 🚀 Python & DevOps Tools  
- **Automation:** `Fabric`, `Invoke`  
- **CI/CD:** `Jenkins`, `GitHub Actions`  
- **Cloud & Containers:** `AWS SDK (boto3)`, `Docker SDK`, `Kubernetes`  

## ⚙️ Python Configuration Management  
- **Using Config Files:**  
  ```python
  import json  

  with open("config.json") as f:  
      config = json.load(f)  
  print(config["api_key"])  
  ```  
- **Environment Variables:**  
  ```python
  import os  
  api_key = os.getenv("API_KEY")  
  ```  
- **Configuration Management Tools:** `Ansible`, `SaltStack`, `Terraform`  

---
# Week 6: Databases
