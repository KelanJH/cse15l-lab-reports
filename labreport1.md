**Lab Report 1 - Remote Access and FileSystem (Week 1)**

**Step 1. Find your CSE15L Account**
To access your course-specific account for CSE15L, you can visit the website:  [Account Info](https://sdacs.ucsd.edu/~icc/index.php) 
Once you're on the website, you can find your account information by entering your UCSD email address and password. 
If you encounter any issues logging in, you can follow the tutorial provided on the website for resetting your password.

**Step 2. Installing VS Code**
Before you start, you need to have VS Code installed on your computer. 
If you don't already have it, you can download it from the website: [Visual Studio Code](https://code.visualstudio.com/)

**Your VS Code should look something like this when you first install it:**

[vscode,png](https://github.com/KelanJH/cse15l-lab-reports/blob/main/vscode.png)

**Step 3. Installing and using Bash**
If you're using Windows, the first step to accessing a course-specific account in CSE is to install Git for Windows. 
This comes with some useful tools that are needed for the process. 
You can download and install Git for Windows by visiting [Git](https://gitforwindows.org/)
After installing Git for Windows, you need to set the default terminal in Visual Studio Code to use the newly-installed Git Bash. 
This can be done by following the steps provided in this post on Stack Overflow: [Git Bash](https://stackoverflow.com/questions/42606837/how-do-i-use-bash-on-windows-from-the-visual-studio-code-integrated-terminal/50527994#50527994) 
By doing this, you'll be able to access the Git Bash terminal from within Visual Studio Code on Windows.

**Step 4. Remotely Connecting**
To connect to a remote computer using ssh, open a terminal in Visual Studio Code and type the command "ssh cs15lsp23zz@ieng6.ucsd.edu" replacing "zz" with the letters in your course-specific account. 
If you are connecting to this server for the first time, you will be prompted with a message asking if you want to continue connecting to the server. 
Type "yes" and then enter your password to complete the login process. 
Once you are logged in, your terminal will be connected to a computer in the CSE basement and any commands you run will be executed on that computer.

**This should be what it looks like when you first connect:** 

![FirstConnect](https://github.com/KelanJH/cse15l-lab-reports/blob/main/first%20connect.png)

**Step 5. Run some Example Commands**
1. Open the terminal on your computer and on the remote computer after ssh-ing (use the terminal in VScode). 
2. Try running the following commands in different ways: 
   "cd" to change directory 
   "ls" to list the files and directories in the current directory
   "pwd" to show the current directory path 
   "mkdir" to create a new directory 
   "cp" to copy a file from one location to another

**Here is an example of one of those outputs:**

![ExampleCommands](https://github.com/KelanJH/cse15l-lab-reports/blob/main/example%20commands.png)

