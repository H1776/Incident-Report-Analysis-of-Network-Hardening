<h1> Incident Report: Analysis of Network Hardening</h1>

<h2>Description</h2>
In this activity, I will be presented with a scenario about a social media organization that recently experienced a major data breach caused by undetected vulnerabilities. To address the breach, I will identify some common network hardening tools that can be implemented to protect the organization’s overall security. Then, I will select a specific vulnerability that the company has and propose different network hardening methods. Finally, I will explain how the methods and tools I chose will be effective for managing the vulnerability and how they will prevent potential breaches in the future. 
<br />

<h2>Scenario</h2>


I am a security analyst working for a social media organization. The organization recently experienced a major data breach, which compromised the safety of their customers’ personal information, such as names and addresses. My organization wants to implement strong network hardening practices that can be performed consistently to prevent attacks and breaches in the future. 

After inspecting the organization’s network, I discover four major vulnerabilities. The four vulnerabilities are as follows:

1. The organization’s employees' share passwords.

2. The admin password for the database is set to the default.

3. The firewalls do not have rules in place to filter traffic coming in and out of the network.

4. Multifactor authentication (MFA) is not used. 

If no action is taken to address these vulnerabilities, the organization is at risk of experiencing another data breach or other attacks in the future. 

In this activity, I will write a security risk assessment to analyze the incident and explain what methods can be used to further secure the network. <br/> <br/>


<h2>Part 1: Select up to three hardening tools and methods to implement</h2>

1. Multifactor Authentication (MFA)
2. Password Policies
3. Patch Updates

<h2>Part 2: Explanation of my Recommendations </h2>

1.	Multifactor Authentication (MFA):<br /> <br />
•	Effectiveness: Implementing MFA adds an extra layer of security beyond just passwords, which can significantly reduce the risk of unauthorized access, especially in scenarios where employees share passwords. By requiring users to verify their identity using multiple factors such as a password and a one-time password sent to their cell phone, MFA can mitigate the impact of compromised passwords or brute force attacks.<br /> <br />
•	Implementation Frequency: MFA should be implemented once for all user accounts and then regularly reviewed and maintained. Additionally, any changes to user roles or access privileges should trigger a review of MFA settings to ensure continued effectiveness.<br /> <br />
2.	Password Policies:<br /> <br />
•	Effectiveness: Enforcing strong password policies, as per NIST recommendations, can mitigate the risk of password-based attacks such as brute force attacks. By requiring passwords to be complex and regularly updated, and by using methods like salting and hashing, the organization can significantly strengthen its defense against unauthorized access.<br /> <br />
•	Implementation Frequency: Password policies should be implemented once and then regularly reviewed and updated as per evolving best practices or changes in NIST guidelines. Regular training and awareness programs should also be conducted to educate employees about the importance of strong passwords and password hygiene.<br /> <br />
3.	Patch Updates:<br /> <br />
•	Effectiveness: Regular patch updates help address known vulnerabilities in software and operating systems, including those that might be exploited in attacks. By promptly applying patches, the organization can close security gaps and reduce the likelihood of successful exploitation by malicious actors.<br /> <br />
•	Implementation Frequency: Patch updates should be applied regularly as soon as they become available from vendors. This requires a proactive approach to monitoring for updates and a systematic process for testing and deploying patches across the network infrastructure.<br /> <br />

<h2>Conclusion</h2>

In conclusion, implementing multifactor authentication, enforcing strong password policies, and regularly applying patch updates are critical network hardening measures that can significantly enhance the organization's security posture and mitigate the vulnerabilities identified in the security risk assessment. These measures not only address specific vulnerabilities but also contribute to a proactive and robust security framework that reduces the risk of future data breaches or attacks. <br />

 <!--
 ```diff
- text in red
+ text in green
! text in orange
