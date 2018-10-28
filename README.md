#openQA

openQA is a testing framework that allows you to test GUI applications on one hand and bootloader and kernel on the other. In both cases, it is difficult to script tests and verify the output. Output can be a popup window or it can be an error in early boot even before init is executed.

Therefore openQA runs virtual machines and closely monitors their state and runs tests on them.
It is one of the unique testing tool.

The testing framework can be divided in two parts. The one that is hosted in this repository contains the web frontend and management logic (test scheduling, management, high-level API)

The other part that you need to run openQA is the OS-autoinst test engine that is hosted in a separate repository.


#Getting Started 

This project deals with the testing of whole installation process of the Fedora 28 and the On Screen Keyboard of the Fedora using the tool openQA.

How to Contribute to this repository

Star this repository using 'Star' button on the top.
Click on Fork Repository using the 'Fork' button on the top.
Clone the forked repository on your PC. Using this command on your Git bash or any terminal with git support : git clone url.
Now create a new branch with this command: git branch branchname and then use that branch by this command: git checkout         branchname.
Go ahead and make changes.
After making changes use this command to add the changes: git add filename, and then git commit -m "message here".
After that use this command: git push origin branchname.
Create a pull request, and wait for Pull Request to get merged.

