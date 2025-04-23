#  This playbook is used to set up a lamp server (linux-apache-mysql-php) #
Note: this works for just Fedora and Ubuntu for now  
1- In the beginning, you have to make sure that your system is up to date by writing this command
  1) If you're using Ubuntu => sudo apt update && sudo apt upgrade
  2) if you're using fedora => sudo yum update && sudo yum upgrade
Note: if you're using Fedora, you also have to make sure that the yum package manager is installed by writing this command: sudo dnf install yum
2- Secondly, you also have to make sure that the Ansible tool is installed by writing this command =>
   1) sudo yum install ansible (on Fedora)
   2) sudo apt install ansible (on Ubuntu)
3- This is the command to run the playbook => sudo ansible-playbook lamp_playbook.yml
4- the sql username: root & password: root
Note: if you wanna open the DB use this commands mariadb -u root -p ( Fedora Users)    mysql -u root -p ( Ubuntu Users)    
