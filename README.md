#               Ansible_Playbook

You Can Clone a Repo Into Your Local Machine : 
git clone https://github.com/adil1806/Ansible_Playbook.git

# Installation_Ansible_On_RHElv8.1
1. sudo yum install python3
2. pip3 install --upgrade pip
3. Create a User on ansible master machine
   
   adduser ansadm
   
   passwd ansadm
4. Switch to ansadm user
5. pip3 install ansible --user
6. sudo dnf install https://dl.fedoraproject.org/pub/epel/epel-release-latest-8.noarch.rpm
7. sudo yum install ansible
8. ansible --version

# Contributing
1. Fork it! Using URL: https://github.com/adil1806/RHEL-CICD-Automate-Playbook.git
2. Create your feature branch: git checkout -b my-new-feature
3. Commit your changes: git commit -am 'Add some feature'
4. Push to the branch: git push origin my-new-feature
5. Submit a pull request

# For AWS provisioning using Ansible 
Go to my repo https://github.com/adil1806/aws_ansible.git
This playbook use to gather info of EC2 Instance like Instance_Id, Image_Id, Key_Name and save the info in CSV format File.
And it will create S3 Bucket and push the object in that Bucket.
