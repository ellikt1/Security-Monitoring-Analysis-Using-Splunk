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
 IAM Dashboard<br/>
<img src="https://i.imgur.com/hoHUXEX.png" height="100%" width="100%" alt="Operating System Deployment"/>

<p align="center">
IAM Dashboard Cont. <br/>
<img src="https://i.imgur.com/5tsnDF1.png" height="100%" width="100%" alt="Operating System Deployment"/>

 

<h2>Dashboard Description </h2>

### Failed Logins Panel
This panel shows the total number of failed login attempts for the current week. The data is displayed in a red color scheme to highlight the critical nature of failed logins. Users can click on the value to drill down into a detailed report of these login failures.

### Weekly Login Success Rate Panel
This panel calculates and displays the success rate of logins for the current week, shown as a percentage with two decimal places. The color scheme ranges from green to red, indicating the success rate level.

### Failed Login Attempts Over Time Chart
This line chart visualizes the trend of failed login attempts over time, updated hourly. Users can click on the chart to access a more detailed search view.

### Failed Login Hours Chart
This column chart shows the distribution of failed login attempts by the hour of the day, helping identify patterns in unsuccessful access attempts. A detailed search view is available through a drilldown link.

### Top Users by Failed Logins Chart
This bar chart identifies the top 10 users with the most failed login attempts for the week. It allows security teams to focus on potentially compromised accounts.

### Failed Login Accounts Chart
This pie chart breaks down the accounts with failed login attempts, providing a visual representation of which accounts are frequently targeted.


<br />
<br />
<br />
<br />

<p align="center">
Better View of This Week's Failed Login Attempts Table  <br/>
<img src="https://i.imgur.com/PuR7IXg.png" height="100%" width="100%" alt="Operating System Deployment"/>


### This Week's Failed Login Attempts Table
This table lists detailed information about each failed login attempt from the current week, including the date, time, computer name, account name, and failure reason. It provides a sorted view for easy analysis.


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

