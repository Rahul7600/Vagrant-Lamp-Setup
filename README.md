# Vagrant-Lamp-Setup


  Vagrant Commands 

1- vagrant init  (Creates a new Vagrantfile in the current directory.) 

2- vagrant up    (Starts and provisions the Vagrant environment as defined in the Vagrantfile)

3- vagrant halt  (Stops the running Vagrant machine but does not destroy it.)

4- vagrant reload (Restarts the Vagrant machine and applies any changes to the Vagrantfile)

5- vagrant destroy (Stops and deletes the virtual machine created by Vagrant)

6- vagrant status (Displays the current state of the Vagrant environment.)

7- vagrant ssh (Logs you into the Vagrant machine via SSH.)

8- vagrant provision (Runs the provisioners (e.g., Ansible, Shell, etc.) specified in the Vagrantfile)

9- vagrant suspend (Saves the current state of the Vagrant machine and suspends)

10- vagrant resume ( Resumes a suspended Vagrant machine)


Debugging Commands

vagrant ssh-config
Outputs SSH configuration for connecting to the machine manually.

vagrant validate
Validates the Vagrantfile for syntax or configuration issues.

vagrant debug
Starts the environment with detailed debug output.
