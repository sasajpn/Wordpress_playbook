Ansible Playbooks
====


#Overview
###・Create EC2 Instance
###・Initial Setting EC2
###・Initial Setting ConoHa VPS
###・Setup WordPress

##Description
####Create EC2 Instance - Create EC2 Instance from local machine
####Initial Setting EC2 - Upgrade Packages and Setting language, localtime, swap area
####Initial Setting ConoHa VPS - Change SSH Port and Open Port by firewalld
####Setup WordPress - Install nginx and php, mysql then setup WordPress

##Usage
####1.Setting Production
####2.Setting Variables in group_vars/
####3.Start ansible-playbook by using below command

` ansible-playbook -i production (playbook name) `
