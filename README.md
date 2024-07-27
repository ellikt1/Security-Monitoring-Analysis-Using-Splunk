<h1>Security Monitoring & Analysis Using Splunk</h1>

 <img src="https://i.imgur.com/nLAyCbi.png" alt="Microsoft Endpoint Configuration Manager" class="header-image">

<h2>Description</h2>
The IAM Login Activity and Security Insights Dashboard is a comprehensive tool designed to enhance the monitoring and analysis of user authentication activities within an organization's IT environment. Built using Splunk, this dashboard provides real-time insights into both successful and failed login attempts, offering valuable information for improving security and ensuring compliance with identity and access management (IAM) policies.
<br />
<br />

Objectives
 
 - <b>Implement a centralized dashboard to track and analyze login activities, enabling early detection and response to potential security threats. </b>
 - <b>Provide detailed insights into successful and failed login attempts, helping to optimize user authentication processes and ensure compliance with IAM policies. </b>
 - <b>Utilize real-time data visualization to support proactive security measures and informed decision-making regarding identity and access management strategies. </b>


<h2>Utilities & software Used</h2>

- <b>VMware Workstation Pro 17.5</b>
- <b>Splunk Enterprise</b>

<h2>Environment</h2>
Splunk was installed on an Ubuntu Server, serving as the central platform for data collection and analysis. To facilitate comprehensive log gathering, the Splunk Universal Forwarder was installed on Windows Server 2022 Virtual Machines. This setup enabled seamless forwarding of security logs from multiple sources to the main Splunk server. The configuration was designed to support real-time data processing and visualization, providing a robust foundation for monitoring and analyzing user authentication activities.
<br />
<br />


<p align="center">
Configuring the Scan <br/>
<img src="https://i.imgur.com/hoHUXEX.png" height="100%" width="100%" alt="Operating System Deployment"/>

<p align="center">
Configuring the Scan cont. <br/>
<img src="https://i.imgur.com/5tsnDF1.png" height="100%" width="100%" alt="Operating System Deployment"/>

 

<h2>Initial Scan </h2>
The initial scan revealed a total of 392 vulnerabilities, categorized as follows:

- <b>Critical Vulnerabilities: 33</b>


- <b>High Vulnerabilities: 119</b>


- <b>Medium, Low, and Informational Vulnerabilities: 240</b>

Missing Microsoft Security Updates:

- A substantial number of critical vulnerabilities were due to missing security updates from Microsoft. These updates are essential as they often contain patches for recently discovered security flaws that can be exploited by attackers.

- Specific examples included vulnerabilities in Windows operating system components that could allow for remote code execution, privilege escalation, and other severe impacts.

Outdated Microsoft Edge:

- Another significant portion of critical vulnerabilities was related to the outdated Microsoft Edge browser. An outdated browser can have multiple security holes that might be exploited to compromise the system.

- The identified issues included vulnerabilities that could be used for remote code execution, information disclosure, and bypassing security features.

<p align="center">
Scan 1 Vulnerabilities <br/>
<img src="https://i.imgur.com/PuR7IXg.png" height="100%" width="100%" alt="Operating System Deployment"/>



<br />
<br />
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>

