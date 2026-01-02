1. System Uptime Verification

Commands used:
uptime

Explanation:
This command displays how long the system has been running since the last boot.



2. User Process Listing

Commands used:
ps -u $USER

Explanation:
This command lists all processes currently running under my user account.



3. CPU Usage Analysis

Commands used:
top

Explanation:
This command shows real-time process activity and helps identify the process using the highest CPU.


4. Background Process Execution

Commands used:
sleep 300 &

Explanation:
This command starts a process in the background, and the jobs command verifies it is running.


5. Process Priority Management

Commands used:
renice 10 <PID>

Explanation:
This command changes the priority (niceness) of a running process to reduce its CPU priority.


6. Memory Usage Monitoring

Commands used:
free -h

Explanation:
This command displays memory usage information in a human-readable format.


7. Disk Space Inspection

Commands used:
df -h ~

Explanation:
This command shows disk space usage of the filesystem where my home directory is located.


8. Shell Identification

Commands used:
echo $SHELL

Explanation:
This command displays the name of the shell currently in use.


9. Output Redirection

Commands used:
uname -a > system_report.txt

Explanation:
This command redirects system information output into a file named system_report.txt.

10. Disk Usage Visualization

Commands used:
ncdu ~

Explanation:
The ncdu command is not installed on this system, and no installation was performed to avoid making configuration changes.
If available, ncdu provides an interactive disk usage visualization of directories and files.
