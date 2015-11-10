How to create, start, and log in to VM:
 * Download and install Vagrant
 * Open command line and type the following commands:
   * vagrant box add titan-basic /dcbrow10/titan-basic.box    
   * vagrant init titan-basic
   * vagrant up
 * Log in (If needed, the username and password are both "vagrant". You should be able to just click the Log In button without entering the password when opening the VM on Virtualbox but for some reason ssh'ing in with Putty still requires the password after I changed the permissions and password settings for sudo and .ssh in the image)

***

* Built VM contains at least one software prerequisite for tool: Java JDK
* Built VM guest operating system contains same operating system as hand-built VM: Lubuntu 15.04

***

Various sources used:
* https://docs.vagrantup.com/v2/getting-started/
* https://www.vlent.nl/weblog/2014/12/19/how-to-create-a-custom-vagrant-box/
* https://scotch.io/tutorials/how-to-create-a-vagrant-base-box-from-an-existing-one
* https://blog.engineyard.com/2014/building-a-vagrant-box
* https://vagrantcloud.com/scheffield/boxes/docker-env-lubuntu-14.04 (original lubuntu box source)
