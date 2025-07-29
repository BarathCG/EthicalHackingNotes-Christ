Today, I installed Kali Linux using Oracle VirtualBox on my Windows 10 computer. I used the Kali Linux Version 2 ISO file which was around 4GB in size.

Tools Used:
  Oracle VirtualBox
  Kali Linux version 2 ISO (4GB)
  Windows 10 (host operating system)

Steps I Followed:
  Downloaded the Kali Linux ISO from the official website.
  Installed Oracle VirtualBox.
  Created a new virtual machine:
  Selected Linux and Debian 64-bit as the version.
  Allocated 2 GB RAM and 20 GB of virtual hard disk space.
  Attached the Kali Linux ISO file to the VM.
  Started the virtual machine and chose the Graphical Install option.
  Completed steps like selecting language, region, username, password, and disk partition.

Error Faced:
  During the installation, I got an error message that said:
  "An installation step failed. The failing step is: Select and install software."

How I Fixed It:
  I checked the network settings in VirtualBox.
  Changed the adapter to NAT mode so the VM could access the internet.
  Restarted the installation process.
  This time, the software installed successfully.


sudo apt install kali-linux-default

Final Result:

I successfully installed Kali Linux version 2 in Oracle VirtualBox and it's now ready for ethical hacking practice.
