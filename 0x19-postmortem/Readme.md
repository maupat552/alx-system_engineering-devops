# MISCONFIGURED FIREWALL
![misconfigured firewall](https://user-images.githubusercontent.com/89969949/228144296-18dff6b5-30af-41bd-b04d-4815c0baea8a.png)

## Issue Summary:
On February 25, 2023, at 3:00 PM Eastern Standard Time, there was an outage that lasted for 2 hours and impacted 75% of the users of our website. Users were experiencing slow load times, error messages, and difficulty accessing certain features on the website.

## Root Cause:
The root cause of the outage was a misconfigured firewall rule that was blocking important traffic to our web servers. This misconfiguration occurred when a recent update was made to our firewall settings.

## Timeline:

3:00 PM: The issue was detected by several customer complaints of slow website performance and error messages.
3:10 PM: The system logs were checked, and it was discovered that there were errors related to the firewall.
3:20 PM: The DevOps team started to investigate the issue and checked the firewall settings.
3:30 PM: The DevOps team identified the misconfigured firewall rule and attempted to fix it.
4:00 PM: After several attempts to fix the rule, it was decided to escalate the issue to the senior DevOps engineer.
4:30 PM: The senior DevOps engineer was able to fix the firewall rule and restore normal traffic flow to the web servers.
5:00 PM: The incident was resolved, and the website was fully operational again.
##  Root Cause and Resolution:
The root cause of the issue was a misconfigured firewall rule that was blocking important traffic to our web servers. The resolution of the issue involved correcting the misconfigured rule in the firewall settings. Once this was done, normal traffic flow to the web servers was restored.

##  Corrective and preventative measures:
To prevent similar incidents from happening in the future, we will be implementing the following corrective and preventative measures:

Regularly review and test firewall rules to ensure that they are properly configured and working as intended.
Develop and implement a process for testing firewall rules before they are deployed to production.
Conduct a review of our incident response process to identify areas for improvement, including escalation procedures and communication protocols.
Schedule regular training sessions for DevOps team members to improve their troubleshooting and problem-solving skills.
Add monitoring alerts for changes to firewall rules, so any misconfiguration can be detected quickly.
To address the issue specifically, we will be implementing the following tasks:

Conduct a review of all firewall rules to ensure that they are properly configured.
Implement a testing process for new firewall rules before they are deployed to production.
Schedule a training session for the DevOps team on troubleshooting firewall issues.
Implement monitoring alerts for changes to firewall rules to detect any misconfigurations quickly.
In conclusion, the misconfigured firewall rule caused an outage that impacted a significant portion of our user base. However, we were able to identify and resolve the issue in a timely manner, and we have taken corrective and preventative measures to ensure that a similar incident does not happen again in the future.
