# Security Infrastructure Design Document

This document outlines the security infrastructure design for the Fictional Company, a retail organization that handles customer payment data.

## AuthN and AuthZ system

- Deploy Active Directory for all the employees to centralize the authentication system.
- Enforce multifactor authentication for all the employees to protect the unauthorized access to any of the services ort resources.
- Enforce employees to set strong passwords with lenght requirements, Character complexity, and prevention of dictionary words in the password using GPOs. Also enforce the employees to change their passwords continuesly after some period, and implement lockout mechanism after some number of failed login atteps.
- Give least privileges to the employees to prevent security insider securty breaches

## External Website Security

- Encrypt the traffic by using SSL/TLS encryption
- Implement firewalls to the incoming traffic to monitor and filter suspicios traffic

## Internal Website Security

- Deploy the private Website interanlly in the domain services to fully cut the public access.
- Implement strong firewall rules to only allow acces to the authorized staff. 

## Remote Access Solution

- Set up secure VPN tunnels to provide the employees access to the services or resources from outside of the office. MFA Enforced!!!


## Wireless Security

- Use the latest wireless encryption protocols to maximize the securty of the wireless network

## Laptop Security Configuration

- Implement full disk encryption to prevent the date breach in case the laptop gets lost or stolen.
- Configure screen lock and BIOS lock with strong passwords.
- If possible disable USB ports from BIOS

## Security and Privacy Policy Recommendations

- Use trusted Payment providers like Stripe to completely offlead the responsibility from the company.
- Enforce the customer data regulations like GDPR.
- Develop a plan on how to handle data breaches including notifying customers