Recall from our lectures that we typically name our read-me files README.md on GitHub.
What does .md stand for? Why we do prefer to use .md extension for README files on GitHub?   

Does the git software index and track empty folders in your project?  Yes  
Does every Git project have a .git folder?  yes.  

What is the purpose of the .git folder in Git projects? Git is a DVCS that grew out of frustration between the Linux kernel developing community and a proprietary VCS software company that maintained and indexed Linux kernel development  

What does the Linux Bash command cd do? (Hint: See the Linux cheatsheet in the lecture notes) Change to home.  

What does the Linux Bash command ls -a do? (Hint: See the Linux cheatsheet in the lecture notes) Formatted listing with hidden files.  

What does the Linux Bash command pwd do? Show current directory.  

Name and briefly describe the three different areas in a Git project. modified, but not staged: This is when the user modifies a project file, but Git/Mercurial has no track of the file changes. If the file is lost or removed unexpectedly, then Git cannot recover the file. staged for commit to the repository: When the developer modifies a file, they can add it to the Git staging area to be later committed permanently to the repository. The staging area is a file, generally contained in the project’s repository (.git directory), that stores information about what will go into the next commit to the repository. The staging area is also sometimes referred to as the index. committed to the repository: Once the staged files are committed to the repository, they become a permanent part of it. They can be later extracted (i.e., checked out) for review or further development.  

What is a Version Control System (VCS)? A brief explanation is enough. Version control is a system that records changes to a file or set of files over time so that you can recall specific versions later.    

Name 6 major benefits of using distributed VCS as opposed to not using any VCS at all for project indexing and maintenance. It was developed in the first decade of the new millennium. Each client has a copy of the central database at their local storage device. Every clone of the central repository with each client is a full backup of the project’s data and history. This VCS paradigm is currently the most popular class of VCS. 

Name the three major historical classes of VCS. Locsl Centralized and Distiributed. 

What is Git and how is it different from GitHub? Git is a version control system that allows developers to track changes in their code. GitHub is a web-based hosting service for git repositories.  

What does git status command do? List all new or modified files to be commited.  

What does git push --all command do? Uploads all local branch commits to Github.  

What does git pull command do? Downloads bookmark history and incorporates changes.    

What is Markdown? (A brief answer is sufficient) Markdown is a way to style text on the web. You control the display of the document; formatting words as bold or italic, adding images, and creating lists are just a few of the things we can do with Markdown.  

How do you make a text boldface in Markdown? (Hint: Read the Markdown cheatsheet in the lecture notes) ** or _ _  

How do you make a text italic in Markdown? (Hint: Read the Markdown cheatsheet in the lecture notes) * or _  

What is the Git command to initialize an empty git project on your local system? git init.  

What do . and .. mean in directory path names (For example, in ./README.md and ../README.md? 

The following steps will guide you to create an empty Git project using the terminal (on macOS / Linux) or Git Bash environment (on Windows).
If you have not set up Git on your system in class before, here is your last chance to do so.
Open your terminal (on Linux or macOS) or Git Bash (NOT Windows CMD or PowerShell) on Windows.
Navigate to your home directory and type the command that shows the path to the current directory on the command line (Hint: Recall the Linux commands to achieve this from our classes or the cheatsheets.) cd  
Select the commands that you have types and the commands output from the command line and paste it into your README.md file for this quiz in the section for this question.
(Hint: You can select text with your mouse, then right click and look for copy option, or alternatively, press ctrl + insert keys together to copy the selected text.)
Create a new folder named testdir in your home directory (where you are).
(Hint: Recall the Linux command for making directories.)
Copy the command and its output again to the README.md file you have created for the quiz.
Change directory to testdir. (Hint: Recall the command to change directory from the Linux cheatsheet and our class) cd dir  
Is this folder testdir already a git repository? Why? Can you prove your answer with the command ls -a (What does this command do?) Yes and directory listing.  
If your answer to the above is YES, then you can safely skip this part.
If your answer is NO, then how would you make this folder a Git project? (Hint: What is the right git command to achieve this?)
Recall the vim software from our lectures and classes. What does it do? 
Using vim create a README.md file and type This is a README.md file for the test git project of quiz1.
How do you save the contents of this file using vim and quit the vim environment? (Hint: Again remember our class discussion and lectures)  commiting changes.  
Once you are out of the vim environment, type cat README.md on the command line and press Enter key.  
What do you see? Copy and paste this command and its output to as answer to this section of your quiz1 README.md file. i see no changes.  
How would you check the status of your test Git project that you have created in this folder? open the folder.  
Paste the git command and its output as your answer to this question in your quiz README.md file.
If you see no changes, you can skip this question.
If you see changes in your git project from the step above, how would you stage and commit those changes to your test project on the command line?
Type those two (or both in one) commands in the terminal and copy/paste the output to your quiz1 README file.
Check the status of your test project one more time on the command line.
Copy/paste the command and its output to your quiz1 README file.
Now type the following command exactly as is in your terminal and press Enter.
cd && rm -rf ./testdir
Explain what you just accomplished with the above command? What does -rf do in the above command?
(Hint: && means perform the first command and if successful, then perform the command that follows &&.) it saves.  


