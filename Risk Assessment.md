# Security Risk Assessment Report

Disclaimer: This project was created as part of my learning journey through the Google Professional Cybersecurity Certificate offered on Coursera. Some activities and content within this project were provided by the course as part of my coursework. All credit for such content belongs to Google and Coursera, and I acknowledge their role in supporting the completion of this project.

### Three hardening tools and methods to implement:
- Firewall maintenance
- Multifactor authentication (MFA)
- Password policies

### Recommendation explanation:

Firewall maintenance would be effective because the organization's firewalls do not have rules in place to filter traffic coming in and out of the network.
A firewall allows or blocks traffic based on a set of rules and if the organization's firewalls do not have rules in place then it cannot do its job properly.
Without defined rules, any incoming or outgoing traffic, including malicious data, can flow freely, putting the organization at risk of cyberattacks, data breaches, 
and unauthorized access. 
Firewall maintenance entails checking and updating security configurations regularly to stay ahead of potential threats. This could be done monthly or firewall rules 
could also be updated in response to an event that allows abnormal network traffic into the network.

Multifactor authentication (MFA) would be effective because the organization currently does not use MFA. 
MFA is a security measure which requires a user to verify their identity in two or more ways to access a system or network. MFA options include a password, 
pin number, badge, one-time password (OTP) sent to a cell phone, fingerprint, and more. 
MFA would significantly strengthens the security of user accounts and access to critical systems. This is particularly important considering that the admin 
password for the database is set to the default. Which means that the password could be easily guessed and the organization is vulnerable to brute force attcks.
MFA can be implemented at any time, and is mostly a technique that is set up once then maintained.

Password policies would be effective because the admin password for the database is set to the default and because the organization’s employees' share passwords.
Password policies are used to prevent attackers from easily guessing user passwords, either manually or by using a script to attempt thousands of stolen passwords 
(commonly called a brute force attack).
The National Institute of Standards and Technology's (NIST) latest recommendations for password policies focuses on using methods to salt and hash passwords, 
rather than requiring overly complex passwords or enforcing frequent changes to passwords. But the organization could start with enforcing basic password polices
and MFA to improve the organization's security posture. Such as: all passwords should be at least eight characters in length, contain upper case and lowwer case letter,
numbers, special characters, and passwords should be updated annually. It would also be highlt beneficial to disable old employees accounts from the system. 
