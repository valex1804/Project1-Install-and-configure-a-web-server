# Project1-Install-and-configure-a-web-server

🚀 This represents my first project, where I implemented a virtual machine that functions as a web server.
I implemented and documented the necessary configuration steps, applying my knowledge in system administration, security, backups, and an automation script for the backup process.
The purpose of this project was to apply my Linux and Python knowledge and to implement them practically in this project.

The web page component is very basic since the focus was not on this aspect. However, I plan to revisit and improve it in the future.
Additionally, I will provide updates to this project, particularly in the areas of security, backup, and the web page.

⚙️ Configuration used:

VM Software: VirtualBox

OS: Ubuntu Server version 24.04.1 LTS

2048 MB RAM

25.00 GB for the OS

5.00 GB additional hard disk for backup

Custom partitioning for Ubuntu Server:
⛃ / (filesystem): 12 GB ,
⛃ Swap space: 2x RAM (4 GB) ,
⛃ /boot: 100 MB ,
⛃ /home: 5 GB ;

👉 In conclusion, this project gave me confidence to tackle real-world scenarios. I realized that mistakes are part of the learning process, and solving them step by step helps me grow.

## Overview of the project :
> 1. Custom partition of Ubuntu server
> 2. Check system after install
> 3. Install ssh
> 4. Create an administrative user for managing remote the server
> 5. Configure and use a static ip
> 6. Generate ssh key for administrative user
> 7. Install ufw and configure
> 8. Configure backup plan ( python script + cronjob)
> 9. Implement cronjob with python script for backup
> 10. Install and configure Apache2
> 11. Install and configure Noip2 and portforwarding for DNS
> 12. Try to acces the Web server
> 13. Lessons Learned and Conclusion

✅ // To access the complete project documentation, which provides a detailed, step-by-step explanation of the entire process, please download and review the attached PDF. // ✅
