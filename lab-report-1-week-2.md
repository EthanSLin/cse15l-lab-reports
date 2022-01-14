# Installing VScode
![Image](screenshot1.png)
* Go to [this link](https://code.visualstudio.com/)
* Follow prompts to install VScode onto your device
# Remotely Connecting
* If you are on Windows, you must first [install OpenSSH](https://docs.microsoft.com/en-us/windows-server/administration/openssh/openssh_install_firstuse)
* Find your course-specific account for CSE 15L [here](https://sdacs.ucsd.edu/~icc/index.php)
![Image](screenshot2.png)
* Open a terminal in VSCode, and type in this command, responding appropriately to all prompts that follow
> ssh *(your account username here)*@ieng6.ucsd.edu
# Trying Some Commands
* Play around with some commands, like "cd ~" and "ls -a"
![Image](screenshot3.png)
* To log out, hit Ctrl+D and run the command "exit"
# Moving Files with scp
* Create a file on your device called "WhereAmI.java, put these contents into it, then run it with "javac" and "java"
![Image](screenshot4.png)
* Run this following command 
> scp WhereAmI.java *(your account username here)*@ieng6.ucsd.edu
# Setting an SSH key
# Optimizing Remote Running