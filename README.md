# Cuckoo
Cuckoo Virtual Machine for Malware analysis

Ubuntu Login:
	Username: cuckoo
	Password: root

Win7 (cuckoo1 VM):
	Username: cuckoo
	Password: cuckoo

Run the following commands to launch cuckoo:

  Create the Virtual Adapter for VirtualBox:
	    $ VBoxManage hostonlyif create
	    $ VBoxManage hostonlyif ipconfig vboxnet0 --ip 192.168.56.1 --netmask 255.255.255.0
    
  Start Cuckoo:
	    $ cuckoo
	    $ cuckoo web (in secondary terminal)
