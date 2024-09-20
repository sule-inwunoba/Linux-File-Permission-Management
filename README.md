# Managing Linux File Permissions for Enhanced Security

## Objective
The File Permissions Management in Linux project aimed to secure a Linux file system by configuring and adjusting file permissions to prevent unauthorized access. The primary focus was on using Linux commands to analyze, manage, and correct permissions, ensuring compliance with security standards. This project was designed to provide hands-on experience in strengthening system security by safeguarding sensitive files and directories.

## Skills Learned
- Proficient use of Linux commands for managing and securing file systems.
- In-depth understanding of file and directory permissions (read, write, execute).
- Ability to secure sensitive directories from unauthorized access by adjusting file permissions.
- Application of security best practices to reduce vulnerabilities.
- Development of problem-solving skills in file system security.

## Tools Used
- Bash Shell for running Linux commands.
- chmod for managing and changing file permissions.
- ls -la for checking file and directory details and permissions.
- Linux file system for simulating real-world security practices.

## Steps

Ref 1: Checking File and Directory Details - 
In this step, I used the ls -la command to check the file and directory details of the /home/researcher2/projects directory, as seen in the image below. This command provided the permissions for each file and subdirectory, displaying who had access to read, write, and execute files.

![4-Using Linux Commands to Manage File Permissions-1](https://github.com/user-attachments/assets/ee13f7d0-79ce-4c8e-a284-5733052be329)


Ref 2: Changing File Permissions - 
Using the chmod command, I altered file permissions to ensure that only authorized users had access to sensitive files. For instance, to modify the permissions for the .project_x.txt file, I removed write access for the group and retained read access for the user, as shown in the following image.

![4-Using Linux Commands to Manage File Permissions-2](https://github.com/user-attachments/assets/be4d5a5e-0aa3-4e38-95df-d1505b8b11fc)


Ref 3: Adjusting Permissions on a Hidden File - 
This image demonstrates the process of adjusting file permissions for hidden files in the directory. By running the chmod u=r,g=r .project_x.txt command, I made the file readable but not writable for both users and groups, ensuring better security for hidden files.

![4-Using Linux Commands to Manage File Permissions-3](https://github.com/user-attachments/assets/20cd6778-f0f8-4531-86f0-a3175c541a18)


Ref 4: Changing Directory Permissions - 
Next, I modified the permissions for the drafts directory to restrict group execution access. This was achieved using chmod g-x drafts, which ensured only the intended user could execute actions within this directory.

![4-Using Linux Commands to Manage File Permissions-4](https://github.com/user-attachments/assets/3c3f91d2-6927-45e2-9c41-a642156a5c0d)


Ref 5: Final Permissions Adjustments - 
The final image shows the results of adjusting permissions across several files and directories. This process ensured that only the necessary users had the appropriate levels of access to each file, enhancing the overall security of the Linux environment.

![4-Using Linux Commands to Manage File Permissions-5](https://github.com/user-attachments/assets/3cfe6106-b43e-4e11-ab11-b77ae0643147)


## Summary
Throughout this project, I used Linux commands to assess and manage file and directory permissions, ensuring compliance with security standards. By carefully analyzing and adjusting these permissions, I safeguarded sensitive data from unauthorized access, effectively securing the Linux environment using best practices. This hands-on experience deepened my understanding of file security in Linux systems.

