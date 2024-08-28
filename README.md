# Automated-Testing-and-Linux-and-Shell-Scripting
**Problem Statement 1**:

Objective: This assignment is designed to test your proficiency in writing and understanding Bash scripts. Please write scripts to solve each of the following problems. Make sure your scripts are executable and well-documented with comments.

Create a Directory Structure:
Write a script that creates the following directory structure:

/home/user/

   ├── projects/

   │   ├── project1/

   │   ├── project2/

   │   └── project3/

   ├── documents/

   └── downloads/

Git clone 

![gitclone](https://github.com/user-attachments/assets/a480d2c4-a844-4fd9-896a-0354b043bab0)

nano dir_struture.sh

![dir_structure](https://github.com/user-attachments/assets/373d254b-02da-44c1-bb0e-86621f06cb39)

git commit & push to main
![dir_structure_push](https://github.com/user-attachments/assets/c537827f-1ad9-496b-b875-2da8349b7cd4)

**Problem statement 2**:

File Backup:
Write a script that takes a directory as an argument and creates a backup of all .txt files in that directory. The backup files should be copied to a new directory named backup with a timestamp.

nano automated_back_seup_Cronjob

![automated back_setup of Cron job](https://github.com/user-attachments/assets/1f7e7163-aa64-4ce8-ad4d-c70bdd7d7621)

Git commit & push 

![automated back_setup of Cron job_push](https://github.com/user-attachments/assets/ad36c6b4-ac12-4ecd-8649-eaded5027266)

**Problem statement 3**:

User Information:
Write a script that displays the following information about the user:

Username

User ID

Group ID

Home Directory

Shell being used

nano user_info.sh

![user_info](https://github.com/user-attachments/assets/861b1eb5-e781-4006-b297-260af996243e)

Git push

![user_info_push](https://github.com/user-attachments/assets/e68f47e8-a273-4ad1-8b96-fdf11fe38ab4)

**Problem statement 4**:

Disk Usage Alert:
Write a script that checks the disk usage of the root filesystem. If the disk usage is above 80%, the script should send an email alert to the system administrator.

nano disk_usage.sh

![Disk_usage](https://github.com/user-attachments/assets/ef287ed3-6440-4a27-882e-70d7ff39251f)

Git commit & push

![Disk_usage_push](https://github.com/user-attachments/assets/533074e9-9b0d-4f6c-a827-2686ec66082b)

**Problem statement 5**:

File Permission Checker:
Write a script that takes a file as an argument and checks if the file has read, write, and execute permissions. The script should display appropriate messages for each permission.

nano file_permission.sh

![file_permission_checker](https://github.com/user-attachments/assets/17880677-cc73-486f-b10f-6d4c4cba8b3d)

git commit & push
![file_permission_checker_push](https://github.com/user-attachments/assets/c00fd412-c90f-4c37-a010-76e95122fea8)

**Problem statement 6**:

Automated Backup:
Write a script that compresses the /home/user/documents directory into a tarball named documents_backup.tar.gz and moves it to the /home/user/backup directory. This script should be scheduled to run daily using cron.

nano automated_backup.sh

![automatedbacku](https://github.com/user-attachments/assets/76f025ad-6209-4af3-942e-dc05a16ec6dd)

git commit & push

![gitautomatedbackup_push](https://github.com/user-attachments/assets/dc854a2e-1289-444f-8a00-93c5d0665880)

**Problem statement 7**:

Process Monitor:
Write a script that checks if a specific process (e.g., apache2) is running. If the process is not running, the script should start the process and log the action to a file.

nano monitor.sh

![processmonitor](https://github.com/user-attachments/assets/764af750-c9a3-4471-8444-dab7221ff8c4)

git commit & push

![processmonitorpush](https://github.com/user-attachments/assets/18efce6d-45e2-4733-9d86-70559275baef)

**Problem statement 8**:

Text File Analysis:
Write a script that takes a text file as an argument and counts the number of lines, words, and characters in the file. The script should display the counts.


