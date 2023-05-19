## Hi there 👋
![Logo](https://github.com/Kaleidoscope-s/Kaleidoscope/blob/main/Klogo.png)
##  **Problem Domain:** :confused:
<div align="center">

Kaleidoscope has been contracted to improve the cybersecurity processes and systems for a client company, focusing on logging, monitoring, and detection of adversarial activity on cloud infrastructure.

</div>

## **Solution:**
<div align="center">

Kaleidoscope, successfully implemented various measures to enhance the overall security posture of the infrastructure. We began by implementing proper IAM best practices, ensuring secure access and control by implementing IAM for the root account and all team members following AWS best practices. This approach ensured least privilege access and proper authentication.

In terms of server hardening and data protection, Kaleidoscope deployed a CIS-compliant Windows Server Domain Controller (DC) hosted on a private subnet of a VPC. To ensure secure remote access, we configured access to the DC only via VPN tunneling. We also implemented encryption at rest to protect sensitive data stored on the server and encryption in transit to secure data communication between the server and other systems. Additionally, Kaleidoscope deployed Sysmon to generate security-relevant system logs, enhancing monitoring and threat detection capabilities.

For the CIS-compliant data server, Kaleidoscope deployed a Linux server instance containing PII and PCI data. They prioritized data protection by ensuring encryption at rest for the data stored on the server and implementing encryption in transit for secure data communication.

In terms of log aggregation and monitoring, Kaleidoscope configured and integrated the SIEM solution CloudWatch. We enabled real-time ingestion of event logs from key assets, including EC2 instances, which facilitated centralized log monitoring and analysis. Additionally, we demonstrated an attack scenario using a Python script with a new library, triggering an event that was ingested by the SIEM solution.

For cloud monitoring, Kaleidoscope utilized VPC Flow Logs to capture and monitor traffic within the AWS Cloud environment. They developed an AWS Lambda function to trigger relevant responses to detected threats, improving automated threat detection and mitigation capabilities. Furthermore, they actively monitored the AWS environment for threat activity, including monitoring security logs for failed SSH attempts on instances.

Overall, Kaleidoscope's comprehensive security implementation encompassed IAM best practices, server hardening, data protection, SIEM integration, and cloud monitoring. These efforts significantly enhanced the security infrastructure at Code Fellows, enabling efficient threat detection, response, and mitigation.

</div>


 <small> *Kaleidoscope is a group of cohorts currently enrolled at Code Fellows OPS Cybersecurity class. This is a collection of our 401 Cybersecurity Engineering Mid-Term project.* </small>

# Meet the team:
### Ademola Olatunbosun

**I am Epidemiologist by profession, US Army Vet, transitioned into Cybersecurity.**

___
[![Image of Ademola](https://github.com/Kaleidoscope-s/-Kaleidoscope/blob/main/gitK.png)](https://github.com/ademo11?tab=repositories) [![Image of Ademola](https://github.com/Kaleidoscope-s/-Kaleidoscope/blob/main/INK.png)](https://www.linkedin.com/in/ademola-olatunbosun/) 

### Joshua Phipps

**I am currently a Georgia National Guard soldier tranistioning into Cybersecurity.** 

[![Image of Joshua](https://github.com/Kaleidoscope-s/-Kaleidoscope/blob/main/gitK.png)](https://github.com/joshp27?tab=repositories) [![Image of Joshua](https://github.com/Kaleidoscope-s/-Kaleidoscope/blob/main/INK.png)](https://www.linkedin.com/in/joshua-phipps-755a20264/) 
___
### Nickolaus Alderete

**US Army Veteran, low voltage electrician transitioning into the cybersecurity realm.**

[![Image of Nick A](https://github.com/Kaleidoscope-s/-Kaleidoscope/blob/main/gitK.png)](https://github.com/Nkalderete?tab=repositories) [![Image of Nick](https://github.com/Kaleidoscope-s/-Kaleidoscope/blob/main/INK.png)](https://www.linkedin.com/in/nickolaus-alderete/) 
___
### Andrew Perry

**I am Andrew**

[![Image of Andrew](https://github.com/Kaleidoscope-s/-Kaleidoscope/blob/main/gitK.png)](https://github.com/Perryandr?tab=repositories) [![Image of Andrew](https://github.com/Kaleidoscope-s/-Kaleidoscope/blob/main/INK.png)](https://www.linkedin.com/in/andrew-perry-0998b7263/) 
___
### Justin "Sage" Tabios

**Howzit My name is Justin 'Sage' Tabios.  What I enjoy most about tech is the gaming sector of it.**

[![Image of Sage](https://github.com/Kaleidoscope-s/-Kaleidoscope/blob/main/gitK.png)](https://github.com/AnnyeongAloha?tab=repositories) [![Image of Sage](https://github.com/Kaleidoscope-s/-Kaleidoscope/blob/main/INK.png)](https://www.linkedin.com/in/justintabios/) 




-->
