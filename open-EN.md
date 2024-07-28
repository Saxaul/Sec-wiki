# Open-ended Questions #

*These questions have no right or wrong answer. They should allow the candidate to provide full responses. The interviewers here are not just looking for complete answers but also keeping track of HOW a candidate responds (rambles, gets distracted, doesn't answer the question, etc.).*

## People Questions ##

1. Do you have a blog and, if so, what is the URL? *@digininja*
2. Do you contribute to open source projects and, if so, which and at what level? *@digininja*
3. How do you participate in the information security community? *@jstnkndy*
4. What conferences do you attend? *@digininja*
5. What conferences have you spoken at? *@digininja*
6. Name a couple of people in the industry that you'd look to for advice/trust their advice. *Asking this to make sure they are active and know who does what, if they are claiming to be wifi experts and don't name people like Josh Wright then they are lying.* *@digininja*
7. What methods or sources of information do you use for keeping up to date in the security industry? *@jstnkndy*
8. If you could have any job in infosec, what would it be an why? *@webbreacher*
9. What is the coolest thing you have done in infosec? *@webbreacher*
10. Why would you like to work here? *@webbreacher*
11. Describe how you learn best? *@webbreacher*
12. What was the last or most interesting tech project you worked on in your personal time *@cdiaz1971*
13. Have you participated in any Capture The Flag (CTF) competitions? *@sml555_*
14. Have you created any CTF challenges (as an organiser)? *@sml555_*

## Tech Questions ##

### General Pentest ###

1. You are performing a blackbox penetration test for a client. The only allowable attack vectors are network and application level attacks. Where do you start?  *@jstnkndy*
    1. Describe how you would find all domains associated with the client *(if they didn’t answer)*
    2. Describe how you would find all network ranges associated with the client. *(if they didn’t answer)*
2. During the penetration test you find an instance of Outlook Web Access belonging to the client. Describe how you would attack this. *@jstnkndy*
    1. Describe how you would find potential usernames to use. *(if they didn’t answer)*
    2. Describe how you would pick which passwords to use. *(if they didn’t answer)*
    3. Describe how you would avoid account lockouts. *(if they didn’t answer)*
3. If you run the following scan without root privileges, describe what would happen: ```nmap www.google.com``` *@jstnkndy*
    1. What kind of scan was performed? *(if they didn’t answer)*
    2. How many ports were scanned? *(if they didn’t answer)*
    3. If you ran the same command as root, describe the differences. *(if they didn’t answer)*
4. You are launching a Metasploit reverse https meterpreter payload against a host that you know is vulnerable to your attack, but once you type “exploit” nothing happens after it launches the attack, how would you debug this (or what would you change to get your meterpreter session?) *@jstnkndy*
5. You have successfully initiated a meterpreter session against a Windows host. What type of post exploitation do you perform? *@jstnkndy*
    1. How would you extract the local password hashes?
    2. How would you gather cleartext credentials from the machine?
        1. In your report, what would your recommendation be to prevent this? *@leesoh*
    3. You attempt to run mimikatz but error occurs, how do you debug this? (or what would you do to try and fix the error?)
6. Using the same meterpreter session as previous, you are able to dump the local machine hashes, describe what you would do with these. *@jstnkndy*
7. You are performing an onsite penetration test. You do not want to perform any active scanning. How would you gather credentials? *@jstnkndy*
    1. What types of attack could you execute with them? *@leesoh*
8. Suppose you have physical access to a machine on a corporate domain that you are testing. It is connected to their network. You don't have credentials for the domain or local machine. You also have your own laptop. How would you begin testing? *@jstnkndy*
9. How would you avoid anti virus?
10. How would you target a database that you know lies behing a jump server with an unkown IP address?
11. What are commonly vulnerable ports/services/applications?
12. You have unprivileged Windows credentials, how can you elevate your privileges?
13. How can SQL Injection lead to remote code execution?
14. You have a SYSTEM shell on an AD workstation. Describe the process you would take to escalate to Domain Admin. *@leesoh*
15. What was your favourite penetration test moment, and why? *@leesoh*
16. When you are on an engagement, how do you manage client data? *@leesoh Look specifically for awareness of the risk of exposure, encryption, and deletion once the engagement is complete.*

### Crypto/Hashes/Passwords ###

1. What is the relevance of WPAD on a penetration test and how can it be leveraged? *@jstnkndy*
2. How would you conduct a pass-the-hash attack using NTLMv1/v2 (or netNTLM if you're a heathen) hashes? *@leesoh Trick question! These hashes cannot be passed.*

### Web Application ###

1. You are performing an application penetration test and you come across a Java applet, describe what you might do with it. *@jstnkndy*
2. What would you inject into an HTML page of a victim to get their Windows computer to send you their password hashes? *@jstnkndy*
3. What tests you would perform in the following scenarios: suppose you are assessing an application, the “forgot password” process consists of 3 steps: *@jstnkndy*
    1. Enter your username
    2. Answer 3 security questions
    3. Set a new password
4. You have found Local File Inclusion in a .php file on a webserver; you want to read the file contents of the local file config.php file on the webserver but the code is being interpreted. How do you gain access to the file contents of config.php? *@jstnkndy*
5. How would you turn a Local File Inclusion against a Linux host into Command Execution? *@jstnkndy*
6. Describe how and where in an application you might test for username enumeration. *@jstnkndy*
7. Are there any security concerns with scoping an authorization cookie to the parent domain? *@jstnkndy*
8. On a Linux host running MySQL, how would you go about gaining command execution leveraging SQL Injection? *@jstnkndy*

### Mobile ###

1. Describe how you can perform Man-In-The-Middle (MITM) attacks (to view and tamper with the traffic) against mobile devices. *@webbreacher*
