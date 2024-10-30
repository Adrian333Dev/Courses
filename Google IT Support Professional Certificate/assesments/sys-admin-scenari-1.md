# Notes

## Improvements

### Scenario 1

- Contracting Hardware Vendors to Provide Employees with Hardware when they get hired, or services when hardware is broken. Also making list of approved Laptops based on employee roles an requirements, as not every role will have the same requirements. For example, while backend devs might need laptops with high ram and processor, 8GB ram and minimal processor would be enough for designers and non-it people. Other option would be that all the employees would same standard laptop models with minimal hardware and they would use VDI solutions like azure virtual desktop for the work that would require more powerfull hardware.
- Adopting Asset Management Tools to keep track of laptops
- Implementing a Domain Controller with Active Directory to centralize user management and access control. Also by combining it with Cloud tools like Microsoft Entra ID company can fully centralize their users idendity and access management.
- Leveragin Active Directory Group Policy Objects to Enhance the security of users like adding strong Password Policies.
- Using Software Installation and Deployment automation tools like PDQ Deploy to Automate Software setup for the employees
- Create pre-configured images for commonly used OSs and Distros in the company to save time for the OS installation and setup.
- Making to documenations and video tutorials for the new employees that would guide them on account creation and software setup

### Scenario 2

#### Problems

- guiding every new employee on how to login consumes a lot of time.
- lack of automation of software setup and installation
- if all the software and hardware kept in a house, the house becomes single point of failure
- Customer data isn't replicated which also makes it single point of failure, and in case that file is corrupted or the hardware that stores the file is broken the data will be lost and it will be imposible or really hard to recover it
- Giving full access to the folders makes that data vunerablew from the security perspective
- Same as replication problem, because there's no backup the data could be lost forever

#### Imrovements

- Creating Video Tutorials and Documentation for the new employees on how to set up their accounts and etc. would save the IT person a lot of time
- Using automated software installation and deployment tools like PDQ deploy will save the IT person a lot of time, and in case any software is needed to be installed, updated or deleted handling it from a centralized tool will improve the osftware management, and also this way Admin could fully disable or prevent employees from installing unwanted software which would imporve the security.
- Migrating the servers to the cloud could improve the availability, redundancy and fault tolerance by using load balancing, data replication, and backup strategies. It also would reduce the overhead of On Premise Servers, as it's unlikely that single It specialist could keep it up.
- Use Group Policy Objects to limit the access of employees prevent the data loss and keep data integrity. Another option would to be to use alternative cloud solutions for the file management like OneDrive.
- Implement ticketing system for the employees, so when they have probelms they would create tickets instead of emailing the IT person which would improve employee management

### Scenario 3

- Purchasing Computers directly from store might not be the most cost efficient option. Chosing some approved Computer models based on employees role and finding a vendor that can offer a discount for the mass purchase of Computers would be more cost efficient. And even more cost efficient option would be choosing a single Computer model with the minimal hardware, and using VDI providers like Azure Virtual Desktop when high end hardware is needed would be a better option.
- Moving servers to the cloud would reduce the overhead of managing on premise server, imrove availablity, redundancy and fault tolarence.
- Disable Employee accounts and all the access they had to any resources in the comany from Active Directory when they leave the company.
- Switch to better Ticketing System after reseacring a better option. Provide employees with training on how to use the software and restrict the usage of any other option for ticketing.
- Use Cloud option for saving backups as it would more secure place to keep the backup, and case it's needed any employee that has right access to the cloud can access the backup without you pyshically being there.