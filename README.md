# demo-nodejs
Tutorials for node.js and express.js

YouTube from freecodecamp


Create SSH Key for github

Command Line:
> cd ~/.ssh
>
If file is not found, create the .ssh folder:
Command Line:
>mkdirf ~/.ssh
>cd .ssh

Generate the ssh key:

Command Line:
>ssh-keygen -t rsa
Enter file in which to save the key:
>jenx_macbook
>Press "Enter" for passphrase
>Press "Enter" for password

The ssh key is generated and folders are created:
jenx_macbook
jenx_macbook.pub

To copy the key to github:
Command Line:
>cat jenx_macbook.pub
Copy the key from "ssh...local"

In Github, go to setting, under "Access", click "SSH"

On the title, type:
jenx_macbook.pub
paste the ssh here copied from terminal

Create key.

Command Line:
>nano config
This will create the file if it doesn't exist or will display the file content

Add the below command to the file:
IdentifyFile ~/.ssh/jenx_macbook

To save the file, type:
ctrl + x
then 'y'
then Enter
