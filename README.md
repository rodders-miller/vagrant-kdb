# vagrant-kdb
Vagrant setup of a basic KDB instance and q CLI with rwlrap configuration.  The default vagrant config uses the libvirt provider and assumes
the availability of the Ubuntu\trusty64 Vagrant box in libvirt format.

To use dowload the linux version of the KX KDB\q https://kx.com/download/ (note this is a limited 32-bit version)

The downloaded Zip file should be paced in the root directory of the project without chaning its name and then call Vagrant up.

Once the Vagrant box is up and running use the Vagrant SSH command to open a console on the VM.  Q then then be run by using the q comnmand 
which is an alias for q run with the rlwrap command for command history etc.
