 # VIRTUAL MACHINE CREATION IN LINUX

 NAME : gayathri m
 
 REG NO : 212223220024
 
 ## AIM
 To Install Virtualbox / VMware Workstation with different flavours of linux.
## PROBLEM STATEMENT
 The aim of this expriment is to Create a virtual machine (VM) in Linux to run a environment for testing and development purposes.

## ALGORITHM

Step 1: Open VirtualBox
Step 2: Go to File -> New to create a new virtual machine.
Step 3: Enter a name for your CentOS VM.Choose Linux as the type and CentOS as the version (or select the closest option available if CentOS is not listed).
Step 4: Select the CentOS ISO image you downloaded. Set the base memory to 1024 MB (1 GB) Allocate 1 processor core Set the disk size to at least 20 GB Complete the configuration by clicking Finish to create the virtual machine
Step 5: Select the created VM, go to Details (or Settings), and navigate to the Network tab. Configure Adapter 1 as NAT (for internet access through the host). Configure Adapter 2 as Bridged Adapter (for direct access to the local network, if needed). Click OK to save network settings.
Step 6: Click Start to boot up the newly created virtual machine. During installation, set a password for the root user. After logging in to CentOS, open a terminal to start using the command line.

## COMMANDS

## Switch to User:
su username

## View IP Address:
ip a

## Create a Directory:
mkdir <directory_name>

## Change to the New Directory:
cd <directory_name>

## Edit the Hostname File:
vi /etc/hostname

## View the Content of the Hostname File:
cat /etc/hostname


## OUTPUT

![Screenshot 2024-11-17 122621](https://github.com/user-attachments/assets/caa4a83a-aaaf-42b5-bdf5-aa193019e6ee)

 
 
## RESULT
 Virtualbox / VMware Workstation with different flavours of linux is successfully installed.
  


