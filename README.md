# Virtual Machine File Manager

## Run
Double click on vm.bat, and after filling out the parameters select transfer type. Then type in your password in the terminal to connect via ssh.

## Parameters
Folder to Copy - Allows users to specify what folder in the copied direcory is desired. Does nothing when a file is requested.

NetID: Your Cornell alphanumerical ID. Not the 6 digit ID number.

VM Directory: /home/$USR$/ - Automatically assumes you are starting from the /home/your-netid-here/ directory, expects a path argument not starting or ending with a slash

Sandwich -  Sandwiches is just for fun. They do nothing.

Local Directory: C:/Users/$USR$/ -  Automatically assumes you are starting from your local account's main drive directory, expects a path argument not starting or ending with a slash

## Example Inputs:
Folder to Copy: Lab_2

NetID: xyz99

VM Directory: /home/$USR$/: Desktop 

Sandwich: Hotdog (CAN BE LEFT BLANK)

Local Directory: C:/Users/$USR$/: Downloads

## PUTTY
Note that Putty and PSCP are both attached in this download. If you already have those added to path, feel free to delete all files except for the vm.bat and the vm_fetcher.py. Please have Python 7 or 10 installed and added to path. 
