__How to create, start, and log in to VM:__
 * Download and install Vagrant and VirtualBox
 * Initialize vagrant box (command line instructions in _italics_)
   * _vagrant box init dcbrow10/bladen-dcbrow10-titan-vagrant_ __or__ save Vagrantfile to local folder on your machine
   * _vagrant up_ //This may take a few minutes, but should add the box and start up the VM in VirtualBox.
 * Log in (If needed, the username and password are both "vagrant". You should be able to just click the Log In button without entering the password when opening the VM on Virtualbox but for some reason ssh'ing in with Putty still requires the password after I changed the permissions and password settings for sudo and .ssh in the image)

***
__Built VM contains:__
* software prerequisites for tool: Java (Java 1.7 OpenJDK)
* the same operating system as hand-built VM: Lubuntu 14.04

***

__Final VM Script:__

- We did not have permission from the authors to distribute Titan. You can access it [here](https://drive.google.com/open?id=0B384dHeXAHG5TXRJMzBSRHV4eWs) if you are CSC 510 teaching staff as noted by [these](https://piazza.com/class/idk9st8m26917?cid=263) instructions, otherwise contact the authors directly to get access to the tool.

***

__Various sources used:__
* https://vagrantcloud.com/scheffield/boxes/docker-env-lubuntu-14.04 (Original vagrant source, could not find an existing stable resource specifically for Lubuntu which I used for my first vm)
* https://docs.vagrantup.com/v2/getting-started/
* https://www.vlent.nl/weblog/2014/12/19/how-to-create-a-custom-vagrant-box/
* https://scotch.io/tutorials/how-to-create-a-vagrant-base-box-from-an-existing-one
* https://blog.engineyard.com/2014/building-a-vagrant-box

