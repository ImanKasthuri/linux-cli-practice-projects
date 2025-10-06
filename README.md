# linux-cli-practice-projects

# Linux File Management Practice

- This project demonstrates basic Linux command-line operations for creating, modifying, copying, moving, searching, and removing files and folders.
  It follows the same structure as the Google IT Support "Creating, Modifying, and Removing Files and Folders in Linux" lab.

## What I Did

## Checked my current directory

- pwd


## Listed all folders and files with details

- ls -l


## Created and entered a new folder

- mkdir practice
- cd practice


## Created new empty files

- touch notes.txt report.txt


## Added text into a file and viewed it

- echo "Hello this is Iman!" > notes.txt
- cat notes.txt


## Copied, renamed, and moved files

- cp notes.txt notes_copy.txt
- mv report.txt final_report.txt
- mkdir backups
- mv notes_copy.txt backups


## Verified structure

- ls -R


## Searched for specific text

- grep "Iman" notes.txt 


## Removed the folder and cleaned up

- cd ..
- rm -rf practice

