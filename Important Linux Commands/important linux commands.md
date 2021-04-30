Docker Commands for Linux
#####
Install docker: Sudo apt- get install docker.io
To run docker for the FIRST time (*using ‘Docker run’ is for starting up a new container): Docker run  
Run a same Docker: Docker start
Pull a Docker image: Sudo docker pull [desired image:desired version]
Run a Docker container: sudo docker run -ti [name of container] bash
List all Docker containers: Sudo docker container list -a Or Sudo docker ps -a
Remove a Docker container: Sudo docker rm [name of container]


Ansible Commands for Linux
#####
Check Ansible version: Ansible --version
Install ansible: sudo apt install ansible
Pull an Ansible container (from a trusted source): sudo docker run -ti [name of location]/[name of file] 
Start up an Ansible container: sudo docker start [name of your Ansible container]
Sttach to your Ansible container so that you can start creating playbooks etc.: sudo docker attach [name of your Ansible container]
Use Ansible to ping: ansible all -m ping
Use Ansible to ping specific groups: ansible [your group name] -m ping
Run an Ansible playbook: ansible-playbook name-of-playbook.yml
