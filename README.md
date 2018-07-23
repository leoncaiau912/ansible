# ansible
#how to use ansible with dynamic amazon ec2 inventory 
export ANSIBLE_HOSTS=/root/gitleon/ansible/ec2.py
export EC2_INI_PAHT=/root/gitleon/ansible/ec2.ini
$ANSIBLE_HOSTS --list
ansible -m ping tag_Name_leon_docker

