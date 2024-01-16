<h1>Incident Report Analysis</h1>

<h2>Description</h2>
This activity will demonstrate the knowledge that I've gained about networks. I will analyze the situation using the National Institute of Standards and Technology's Cybersecurity Framework (NIST CSF) and create an incident report of my findings.
<br><br>



<h2>Scenario:</h2>

I'm a cybersecurity analyst working for a multimedia company that offers web design services, graphic design, and social media marketing solutions to small businesses. My organization recently experienced a DDoS attack, which compromised the internal network for two hours until it was resolved.<br><br>
During the attack, my organization’s network services suddenly stopped responding due to an incoming flood of ICMP packets. Normal internal network traffic could not access any network resources. The incident management team responded by blocking incoming ICMP packets, stopping all non-critical network services offline, and restoring critical network services. <br><br>
The company’s cybersecurity team then investigated the security event. They found that a malicious actor had sent a flood of ICMP pings into the company’s network through an unconfigured firewall. This vulnerability allowed the malicious attacker to overwhelm the company’s network through a distributed denial of service (DDoS) attack. <br><br>
To address this security event, the network security team implemented: <br>
<li>A new firewall rule to limit the rate of incoming ICMP packets</li>
<li>Source IP address verification on the firewall to check for spoofed IP addresses on incoming ICMP packets</li>
<li>Network monitoring software to detect abnormal traffic patterns</li>
<li>An IDS/IPS system to filter out some ICMP traffic based on suspicious characteristics</li><br>
As a cybersecurity analyst, I'm tasked with using this security event to create a plan to improve my company’s network security, following the National Institute of Standards and Technology (NIST) Cybersecurity Framework (CSF). I will use the CSF to help navigate through the different steps of analyzing this cybersecurity incident and integrate my analysis into a general security strategy:<br>
<li><b>Identify</b> security risks through regular audits of internal networks, systems, devices, and access privileges to identify potential gaps in security. </li>
<li><b>Protect</b> internal assets through the implementation of policies, procedures, training and tools that help mitigate cybersecurity threats. </li>
<li><b>Detect</b> potential security incidents and improve monitoring capabilities to increase the speed and efficiency of detections. </li>
<li><b>Respond</b> to contain, neutralize, and analyze security incidents; implement improvements to the security process. </li>
<li><b>Recover</b> affected systems to normal operation and restore systems data and/or assets that have been affected by an incident. </li><br>

- <b>[APPLYING THE NIST CSF](https://drive.google.com/file/d/1414G4mShuGsJxu-XXn1KLHzas1XxpdbS/view?usp=drive_link)</b>
<br><br><br>



<h2>Incident Report Analysis </h2>

<table>
  <tr>
  <tr><center></center></tr><tr>
    <th><th><th><th>
  </tr>
  <tr>
    <td>Summary</td>
    <td>Earlier today, the incident management team reported to the cybersecurity team that our organization recently experienced a DDoS attack. This compromised the internal network for approximately two hours and caused the organization’s network services to suddenly stop responding due to an incoming flood of ICMP packets. The normal internal network traffic could not access any network resources. In response, our team went into the network and put up a defense by blocking the malicious attack to prevent further damage and work on restoring the system.</td>
  </tr>
    <tr>
    <td>Identify</td>
    <td>A threat actor attacked the company’s internal network by flooding the network with ICMP packets. Action needed to be taken to secure the network and restore it back to normal (with a better defense to prevent this from happening again in the future).</td>
  </tr>
      <tr>
    <td>Protect</td>
    <td>The team has implemented the following measures: a new (and updated) firewall system that could detect incoming ICMP packets and build better protection in the network by fixing the vulnerability that was breached from the attack; install an IDS/IPS system that could monitor incoming suspicious ICMP packets.</td>
  </tr>
        <tr>
    <td>Detect</td>
    <td>Our team configured the new firewall with source IP address verification that will monitor the company’s network system for any future suspicious activity and block any incoming illegal packets.</td>
  </tr>
          <tr>
    <td>Respond</td>
    <td>Moving forward, our cybersecurity team will put in the work to isolate affected systems to prevent disruption to the workflow across the network. Afterwards, we’ll look into the network logs to see if there were any other suspicious activities that we might have missed. Then we will report this incident to upper management and any appropriate legal authorities that also need to be notified.</td>
  </tr>
            <tr>
    <td>Recover</td>
    <td>With the network systems being affected by the DDoS attack and flooding of ICMP packets, the system would need to be restored to be able to function again. Once that’s complete, our newly configured firewall will block any future incoming flood attacks from attacking the network again. As soon as the system is restored and the firewall is up and running, the online business can resume back to its normal activities. </td>
  </tr>
              <tr>
    <td>Reflection/Notes</td>
    <td>NA </td>
  </tr>
</table>



<!--
 ```
 This Incident Report Analysis Repository contains the following:
 Incident Report Analysis

 The scenario listed above is taken from one of the Activities sections provided by the Google Career Cybersecurity Certificate.
```
--!>
