# Security Risk Assessment Report

Disclaimer: This project was created as part of my learning journey through the Google Professional Cybersecurity Certificate offered on Coursera. Some activities and content within this project were provided by the course as part of my coursework. All credit for such content belongs to Google and Coursera, and I acknowledge their role in supporting the completion of this project.

Select up to three hardening tools and methods to implement
- Firewall maintenance
- Multifactor authentication (MFA)
- Password policies

## Memo
Three hardening tools the organization can use to address the vulnerabilities
found include:
1. Implementing multi-factor authentication (MFA)
2. Setting and enforcing strong password policies
3. Performing firewall maintenance regularly
MFA requires users to use more than one way to identify and verify their
credentials before accessing an application. Some MFA methods include
fingerprint scans, ID cards, pin numbers, and passwords.
Password policies can be refined to include rules regarding password length, a
list of acceptable characters, and a disclaimer to discourage password sharing.
They can also include rules surrounding unsuccessful login attempts, such as
the user losing access to the network after five unsuccessful attempts.
Firewall maintenance entails checking and updating security configurations
regularly to stay ahead of potential threats.

Explain your recommendations

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

## Memo
Enforcing multi-factor authentication (MFA) adds an additional layer of security
beyond a password. It will reduce the likelihood that a malicious actor can
access a network through a brute force or related attack since additional effort
is required to authenticate in more than one way. MFA may also reduce the
likelihood of people sharing passwords. Since the recipient of the shared
password would need to possess additional authentication besides a password,
MFA makes it less useful to share passwords, thereby making passwords less
likely to be shared.

Creating and enforcing a password policy within the company will make it
increasingly challenging for malicious actors to access the network. Policies
such as suspending the account after a certain number of logins can prevent
successful brute force attacks. Increasing password complexity, requiring more
frequent password updates, and not allowing passwords to be reused also help
stall malicious actors from infiltrating the network.

Firewall maintenance should happen regularly. Network administrators should
ensure that firewall rules are in place that reflect the most up to date standards
for allowed and denied traffic. Traffic from sources that are suspicious should be
placed on a denied traffic list. Firewall rules should be updated whenever a
security event occurs, especially an event that allows suspicious network traffic
into the network. This measure can be used to protect against various DoS and
DDoS attacks.
