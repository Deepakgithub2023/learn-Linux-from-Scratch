While working with Linux systems, I explored how the file system is structured and organized. Here’s a quick breakdown 👇

📁 Important Directories:

/etc → Configuration files
/var → Logs & frequently changing data
/usr → Installed applications & libraries
/boot → Boot-related files

👤 User Directories:

/home → User files
/root → Root user home
/opt → Third-party software

⚡ Temporary & System Directories:

/tmp → Temporary files
/proc & /sys → System & kernel info
/dev → Device files

🔗 Interesting Fact:
Directories like /bin, /lib, /sbin are now symbolic links to /usr/* in modern Linux systems.

💡 Understanding this structure is essential for DevOps, System Admin, and troubleshooting tasks.
<img width="1024" height="1536" alt="linux life system" src="https://github.com/user-attachments/assets/21c7249f-b939-44bd-88be-34f62ceff8f6" />

###################################################################################################################################################
Managing users effectively is crucial for maintaining security, access control, and system stability in Linux systems.

🔹 Key Highlights:
✔️ Understand core files: /etc/passwd, /etc/shadow, /etc/group
✔️ Create users with useradd & adduser
✔️ Manage passwords & enforce policies using passwd & chage
✔️ Modify users with usermod
✔️ Delete users securely with userdel
✔️ Handle groups & permissions efficiently
✔️ Grant sudo access for controlled privilege escalation

<img width="1024" height="1536" alt="user-managment" src="https://github.com/user-attachments/assets/9165b368-423b-40aa-992f-d620daee837d" />

