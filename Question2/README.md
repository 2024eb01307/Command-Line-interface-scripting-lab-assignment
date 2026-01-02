<img width="1919" height="256" alt="image" src="https://github.com/user-attachments/assets/a9249438-41c9-42e9-85b5-c135a5c54c42" />1. Project Workspace Setup

Commands used:
mkdir documents

Explanation:
This command creates a directory named documents inside my home directory.

2. File Creation

Commands used:
touch plan.txt

Explanation:
This command creates an empty file named plan.txt inside the documents directory.

3. Content Addition

Commands used:
echo "Complete project tasks by Friday" > plan.txt

Explanation:
This command writes sample project text into the plan.txt file.

4. File Metadata Verification

Commands used:
ls -l plan.txt

Explanation:
This command displays the file permissions and ownership details, showing that I am the owner.

5. File Duplication

Commands used:
cp plan.txt plan_copy.txt

Explanation:
This command creates a copy of plan.txt named plan_copy.txt.

6. Directory Renaming

Commands used:
mv documents project_documents

Explanation:
This command renames the documents directory to project_documents.

7. Archival Structure

Commands used:
mkdir project_documents/archive

Explanation:
This command creates an archive subdirectory inside project_documents.

8. File Organization

Commands used:
mv project_documents/plan_copy.txt project_documents/archive/

Explanation:
This command moves the copied file into the archive directory.

9. Recursive Listing

Commands used:
ls -R project_documents

Explanation:
This command lists all files and subdirectories recursively to show the complete directory structure.

10. Path Verification

Commands used:
realpath project_documents/archive/plan_copy.txt

Explanation:
This command displays the absolute path of the plan_copy.txt file after it was moved.



XXXXXXXXXXXXXXXXXXXXXXXX----------------XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
