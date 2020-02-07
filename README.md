# The-Unix-Workbench
All Tasks and Assignments of this course

# (SEC) Navigating the Command Line Exercises

# Set your working directory to the root directory.
ans) cd /
# Set your working directory to your home directory using three different commands.
ans) 
1) cd ~
2) cd /home
3) cd 
# Find a folder on your computer using your file and folder browser, and then set your working directory to that folder using the terminal.
ans)
ls //so that you can find the folder name in the current directory
 \ncd directory_name 
# List all of the files and folders in the directory you navigated to in #3.
ans)press ls'

# Create a new directory called workbench in your home directory.
1) cd ~
2)sudo mkdir workbench
# Without changing directories create a file called readme.txt inside of workbench.
ans) sudo nano workbench/readme.txt
# Append the numbers 1, 2, and 3 to readme.txt so that each number appears on its own line.
ans) echo "1,2,and 3" >> readme.txt
# Print readme.txt to the command line.
ans) cat readme.txt
# Use output redirection to create a new file in the workbench directory called list.txt which lists the  files and folders in your home directory.
ans) i will write ans after sometime
# Find out how many characters are in list.txt without opening the file or printing it to the command line.
ans) wc list.txt

# Create a file called message.txt in your home directory and move it into another directory.
1) nano message.txt
2) mkdir newfolder
3) mv message.txt newfolder
# Copy the message.txt you just moved into your home directory.
cp messsage.txt /home
# Delete both copies of message.txt. Try to do this without using rm.

