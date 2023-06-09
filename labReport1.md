# CSE 15l Lab Report 1 - Kiko Pan 


1. First, if you haven't already reset the password for your CSE15L account, go to the link attached [here](https://sdacs.ucsd.edu/~icc/index.php) and it will ask for your UCSD username and your PID. 

2. Once you've entered that, you should see a CSE15l account associated with your information. Click that and follow the steps to reset your password. 

3. When you've done that, you'll need to download VSCode on your device. To download [VSCode](https://code.visualstudio.com/), follow the instructions on the site to download the latest version. 

4. Once you finish downloading VSCode and you open the app on your device it should look something like this. Make sure you are downloading the one that is compatible with your device. <img src="https://code.visualstudio.com/assets/docs/getstarted/tips-and-tricks/getstarted_page.png" width="750" height="500"> 


5. Next, you're going to want to open a terminal on VSC by doing *Ctrl or Command + `* or you can use menu option at the top where it says Terminal and navigate to the New Terminal option.

6. *Additional step for Windows users only:* You will need to downlaod [git](https://gitforwindows.org/) in order to get started. [Here](https://stackoverflow.com/questions/42606837/how-do-i-use-bash-on-windows-from-the-visual-studio-code-integrated-terminal/50527994#50527994) is a helpful link on how to use bash on windows. 

7. When you've opened the terminal, you will want to enter the following into your terminal but you will need to replace the 'zz' before the @ with your unique username. The $ does not need to be included.     
``` $ ssh cs15lsp23zz@ieng6.ucsd.edu ```

8. You should get a message like the following. Reply Yes and enter your password when prompted.
``` ⤇ ssh cs15lsp23zz@ieng6.ucsd.edu
The authenticity of host 'ieng6.ucsd.edu (128.54.70.227)' can't be established.
RSA key fingerprint is SHA256:ksruYwhnYH+sySHnHAtLUHngrPEyZTDl/1x99wUQcec.
Are you sure you want to continue connecting (yes/no/[fingerprint])?
```

9. When your terminal is connected to the CSE basement server it should look something like this! The commands you run on your terminal should run on the CSE computer. 
```# Now on remote server
Last login: Sun Jan  2 14:03:05 2022 from 107-217-10-235.lightspeed.sndgca.sbcglobal.net
quota: No filesystem specified.
Hello cs15lsp23zz, you are currently logged into ieng6-203.ucsd.edu

You are using 0% CPU on this system

Cluster Status 
Hostname     Time    #Users  Load  Averages  
ieng6-201   23:25:01   0  0.08,  0.17,  0.11
ieng6-202   23:25:01   1  0.09,  0.15,  0.11
ieng6-203   23:25:01   1  0.08,  0.15,  0.11

Sun Jan 02, 2022 11:28pm - Prepping cs15lsp23
```
<img src = "0E5QU1d7g8IkmS0eifkEPmvOnwAJab6ZlybG8XEn0Hk5VvJ7mn8khByx0Of-yIta2Ixq0xS3REXrgQuRGvlJMxlKQKeZywL0iJUnC9RilFjEy9qhK2Ffrhyqytaw.png" width = '600' height ='500' >

10. When you are connected to the CSE server, you can test some of the following commands in the terminal.
* ```cd ~ ``` Changes to home directory. 
* ```cd ``` "Change Directory" - used to switch the current working directory to the given path. 
* ```ls -lat ``` Lists content directory. 
* ```ls -a```Shows all the files in the current directory. 
* ```ls <directory>``` where ```<directory>``` is ```/home/linux/ieng6/cs15lsp23/cs15lsp23abc```, where the ```abc``` is someone elses' username. This lists content directory of user. 
* ```cp /home/linux/ieng6/cs15lsp23/public/hello.txt ~/``` Copies directory. 
* ```cat /home/linux/ieng6/cs15lsp23/public/hello.txt``` Prints the contents of one or more files given by the paths.

Below is an example of how your terminal should look when testing out some of these commands! 
<img src = "total 112.png" width = '600' height ='400' >

11. Now you know how to log into a course specific account on ```ieng6```! To exit the remote server in terminal you can either type ```exit``` in terminal or do Ctrl-D.
