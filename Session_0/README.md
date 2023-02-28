# Londrina-Course-January-2023

**Genome assembly by Oxford Nanopore sequencing**

**Session_0**

Session objectives: Install virtual machine and software for the course


**Step 1:**
The virtual machine and tools must be installed before the course starts. Linux and MACos users can use directly their os.
For windows users (and others), we suggest to install virtualbox (V.6.1 **-NOT 7-**) on your computers (https://www.virtualbox.org).  
You may download a pre-build virtual machine here https://www.osboxes.org/ubuntu/ (Username: osboxes; Password: osboxes.org) https://www.eugenetoons.fr/utiliser-un-fichier-vdi-dans-virtualbox/
Alternatively, you can follow the  guide for a personalized build and virtual machine : https://ubuntu.com/tutorials/how-to-run-ubuntu-desktop-on-a-virtual-machine-using-virtualbox#1-overview or https://www.arcserve.com/blog/dead-simple-guide-installing-linux-virtual-machine-windows or https://www.youtube.com/watch?v=hvkJv71PsCs
I propose to download Ubuntu V. 22.04 as Linux os to be installed on the virtual machine. 
**important: a minium of 25 go is required for the virtual hard disk and to run the course**    
**The virtual machine should be functional the firt day of the course in order to not lose time.  **

Todo 
1_go to settings ->Keyboard: enter your keyboad type (if not set during installation)
2_Open Terminal -> Type: sudo apt-get -y install dkms build-essential and enter the password. Type Y
3_in the bar above click on insert cd picture guest addition
4_ run VBoxLinuxAdditions.run as sudo 
4_sudo usermod -a -G vboxsf $USER

 If you want to share files between the computer's OS and the the virtual machine, see this tutorial. Sharing files https://medium.com/macoclock/share-folder-between-macos-and-ubuntu-4ce84fb5c1ad

**Step2:**

You need to install Anaconda on your comuter (https://www.anaconda.com/products/distribution). Anaconda is an open source Python distribution, with a very simple way to install software.
Download the Anaconda installer from the Linux virtual machine (or from Linux or MACos systeme for these users): 64-Bit (x86) Installer (737 MB) file and run it as follow:
In a Terminal: chmod 755 [Anaconda file]
 ./[Anaconda file]


**Step3:**

Start jupyter notebook from a terminal

Type: Jupyter notebook 
Type ENTER
The web browser should open a new page with the Jupyter default page. 
Type New (with python as dafault language)

Now Jupyter is functional on your virtual machine
Go to Session_0 directory and open session_0_jupyter_notebook_basics.ipynb to learn how to use Jupyter
