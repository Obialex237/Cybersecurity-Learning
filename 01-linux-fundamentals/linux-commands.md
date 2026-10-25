# Linux Fundamentals for SOC Analysts
## Project Objective

Learn essential Linux commands used in system administration,
troubleshooting, and cybersecurity investigations.

## 1. Navigation Commands

### pwd
Displays the current working directory.

### ls
Lists files and directories.

### cd
Changes the current directory.

Example:
cd /var/log

## 2. File Inspection Commands

### cat
Displays file contents.

Example:
cat example.log

### less
Allows you to read a file page by page.

Example:
less example.log

### head
Displays the first lines of a file.

Example:
head example.log

### tail
Displays the last lines of a file.

Example:
tail example.log

## 3. Searching Logs

### grep
Searches text for a specified pattern.

Example:
grep -i "failed" example.log

## 4. File Permissions

### ls -l
Displays file permissions and ownership.

### chmod
Changes file permissions.

### chown
Changes file ownership.

## 5. System Information

### whoami
Displays the current username.

### id
Displays user and group information.

### uname -a
Displays Linux system information.

## 6. Security Relevance

SOC analysts may use these commands to:

- Inspect system logs.
- Investigate failed authentication attempts.
- Identify file permission issues.
- Understand user accounts and groups.
- Collect information during an investigation.

## What I Learned

I will document the commands I practice, what they do,
and how they can support security investigations.
