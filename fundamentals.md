---
layout: default
---

# Fundamental Practices

## Installing And Using SSH

To begin, I open up the terminal in my Kali Linux VM and enter the command "sudo apt install openssh-server"

I create a test folder for this lab and use a chain of CD commands to get into the test folder.

![basics](basics 1.png)

I type an ipconfig command to get my IP address for this VM.

I go to my Windows 10 box and download Putty and type the IP address in the host name.

![basics](basics 2.png)

I successfully log into my Kali SSH via my windows Putty, demonstrating a successful SSH install and connection.

## Securing Windows With Password Complexity

In this lab I set up my windows operating system to force users to have complex passwords.

First, open the run command and type 'gpedit.msc'

Then I open Windows Settings -> Security Settings -> Account Policy -> Password Policy

From here I can edit the password requirements and enable/ disable complexity requirements.

These requirements are not on by default, so enabling them is a good security practice most Windows users are not utlizing.



