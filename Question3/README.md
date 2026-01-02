1. File Creation

Commands used:
echo "This is sample data" > sample_data.txt

Explanation:
This command creates a file named sample_data.txt and writes sample text into it.


2. Hard Link Creation

Commands used:
ln sample_data.txt sample_hard.txt

Explanation:
This command creates a hard link named sample_hard.txt pointing to the same data as sample_data.txt.


3. Symbolic Link Creation

Commands used:
ln -s sample_data.txt sample_soft.txt

Explanation:
This command creates a symbolic link that references the original file sample_data.txt.


4. Inode Verification

Commands used:
ls -i sample_data.txt sample_hard.txt sample_soft.txt

Explanation:
This command displays the inode numbers of the original file, hard link, and symbolic link.



5. Inode Analysis

Explanation:
sample_data.txt and sample_hard.txt share the same inode number because a hard link points to the same inode.
The symbolic link has a different inode because it only stores the path to the original file.


6. File Metadata Inspection

Commands used:
ls -l sample_data.txt

Explanation:
This command displays detailed file information such as permissions, ownership, size, and timestamps.


7. Disk Usage Check

Commands used:
du -sh ~

Explanation:
This command shows the total disk usage of my home directory in a human-readable format.


8. File Size Overview

Commands used:
ls -lh ~

Explanation:
This command lists all files in the home directory along with their sizes in a human-readable format.


9. Link Deletion Test

Commands used:
rm sample_soft.txt

Explanation:
This command deletes the symbolic link without affecting the original file sample_data.txt.


10. Disk Utility Demonstration

Commands used:
du -h .
df -h

Explanation:
The du command shows disk usage of files and directories, while df displays overall filesystem disk space usage.
