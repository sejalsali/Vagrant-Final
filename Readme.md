Here, first the local machine is installed with vagrant in the git bash and this can be verified by the command vagrant –v. 
After the vagrant is installed and version verified, we initialized the vagrant by using the command vagrant init which creates a vagrantfile in the current directory. 
Here, we have task of changing the host machine and assigning public and  private networks along with spinning the virtual machines and all these tasks are configured in vagrantfile.
All this tasks are verified by using vagrant status.
Then as vagrant status shows running, we have connected via ssh to ubuntu and centos i.e. to the multi machine topology task.
This is verified by using vagrant ssh name command.
Later the apache homepage is also displayed on the browser.
