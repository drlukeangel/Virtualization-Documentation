ms.ContentId: F21F148C-794C-408D-A480-D19D893A4DB7
title: Step 9: Create a Linux guest virtual machine

# Create a Linux guest virtual machine 

In this step we will create a virtual machine and install the 64-bit edition of Ubuntu 14.04.2 LTS with the file name ubuntu-14.04.2-desktop-amd64.iso. 

If you have another distribution that you would rather use, make sure it will work correctly by checking [Linux and FreeBSD Virtual Machines on Hyper-V](https://technet.microsoft.com/en-us/library/dn531030.aspx)

1. Download the .iso from [http://www.ubuntu.com/download/desktop](http://www.ubuntu.com/download/desktop) and save the file to your \\downloads directory.
2. In Hyper-V Manager, click on the **Action** menu > **New** > **Virtual machine**. 
3. In the virtual machine wizard, make the following choices:

| **Page** | **Entry** |
|:-----|:-----|
|Name:						|Ubuntu Desktop VM 												|
|Generation: 				|Generation 1  													
|Startup Memory:			|1024 and don't select dynamic memory 							|
|Configure networking: 		|External (this is the Virtual Switch you created in Step 4)	|
|Connect virtual hard disk: |Create a virtual hard disk (keep the other default values) 	|
|Installation Options:		|Install an operating system from a bootable CD/DVD-ROM. Under **Media**, select **Image file (iso)** and then click **Browse** to point to the .iso file. 			|


4. When everything looks right, click **OK**. 

5. After the virtual machine is created, you need to right-click on the virtual machine and select Connect. This will start the virtual machine and it should boot into the Ubuntu setup program.



## Next step:
