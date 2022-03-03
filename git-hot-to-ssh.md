How to make ssh key
-------------------

Run these commands in cmnd line:

1) Ssh-keygen -t ed25519 -C "youremailhere"
2) Enter name of the file
3) Enter password for the key (or not) 
4) Will be generated file without extention - your privaye key, do not share this!
5) 'Name'.pub - public version of the key in text file
6) Add public version in account setting on Your GithUB Page
7) Use 'ssh-add "name of private key"'
8) You can check list of added ssh keys using 'ssh-add -l'

