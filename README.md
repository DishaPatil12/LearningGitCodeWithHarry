# WEB DESIGN AND USER EXPERIENCE ASSIGNMENT 1
## NAME : **DISHA SUNIL PATIL**
## NEU ID : **002768900**

Introduction to Git
Git is a distributed version control system.It is a best practice for managing and tracking changes to the software code by tracking every individual change by each contributor and helping prevent concurrent work from conflicting. It is utilized by software teams to manage changes to source code over time. It has features like Branching and merging,Traceability, Collaborative Coding, Security, Easy hosting and many more

Main Workflow

Working directory <=> Staging area <=> local repository<=> remote repository

#### How to use git for creatng repositories for projects and hosting them
Prerequities =>
Step 1: Setting up the enviornment by installing Git
Step 2: Create repository and make it private


Step 3: Creating SSH keys 
        Introdution to SSH keys
        You are giving control / access of our github account to your computer. For that you have to deploy a SSH key



Step 4: Go inside generating SSH keys and create key using email id  
        CMD =>  $ ssh-keygen -t ed25519 -C "patil.dis@northeastern.edu" [Refer to the link Generating new SSH keys]
        This will generate a SSH key which we will deploy.

Step 5: For adding SSH agent
        CMD => eval "$(ssh-agent -s)"   	[ Refer to the link Adding your SSH key to the ssh-agent]

Step 6: To add SSH private key to SSH agent 
        CMD => ssh-add ~/.ssh/id_rsa       [ Refer to the link Adding your SSH key to the ssh-agent]

Step 7: To deploy this SSH key to your github account
        CMD =>cat ~/.ssh/id_rsa.pub   [Refer to link addition of SSH keys to your account ]
        



        Links:
                    Generating new SSH keys
                    https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent

                    Adding your SSH key to the ssh-agent
                    https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account

                    addition of SSH keys to your account:
                    https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account

SSH Keys 
You are giving control / access of our github account to your computer
For that you have to deploy a SSH key

Go inside generating SSH keys and create key using email id  

=>  $ ssh-keygen -t ed25519 -C "dishampatil@gmail.com" [Generating new SSH keys]


This will generate a SSH key which we will deploy using the 


=>eval "$(ssh-agent -s)"   	[ Adding your SSH key to the ssh-agent]
This will add the ssh-agent in the background


 
=>ssh-add ~/.ssh/id_rsa   [ Adding your SSH key to the ssh-agent]

You have added the SSH private key to SSH agent
Now you have to just deploy this SSH key to your github account
=>cat ~/.ssh/id_rsa.pub   [This is inside about addition of SSH keys to your account ]















###Git Command Line Basics###







