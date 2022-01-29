# Linux based File Explorer
A file explorer for linux systems that runs on terminal
## Prerequisites

**1. Platform:** Linux 

**2. Software Requirement:**
* G++ compiler
   * **To install G++ :** ```sudo apt-get install g++```

## Steps to run the project
- Open your terminal with present working directory as the project folder. Then run the this command.
    ```g++ -o main main.cpp```
- Then enter this command to start application, 
    ```./main```
    ## Assumptions
* Default mode is Normal mode and press **:** to switch to Command mode.
* Press **ESC** key to go back to normal mode from command mode.
* Press **q** key from normal mode/command mode to exit from program.
* In Normal Mode, assumed the max window size as 6.
* In Command mode, to edit the command use backspace only.
* Preferable to open terminal in full size. if one record spans over more than one line then navigation won't work correctly.
* if **Enter** is pressed on text files and it will be opened in **vi** editor.
* In **command mode** paths are 3 types
* one is ~/dir1/dir2 , it means you are entering path which is relative to your home directory.
* another one is /dir1/dir2 , it means it is from root
* another one is dir1/dir2 , it means you are entering path which is relative to your current working directory.