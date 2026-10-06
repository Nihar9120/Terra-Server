Terraform Install :
===================
--> Install Terraform On Ubuntu OS 

$ wget -O - https://apt.releases.hashicorp.com/gpg | sudo gpg --dearmor -o /usr/share/keyrings/hashicorp-archive-keyring.gpg

$ echo "deb [arch=$(dpkg --print-architecture) signed-by=/usr/share/keyrings/hashicorp-archive-keyring.gpg] https://apt.releases.hashicorp.com $(grep -oP '(?<=UBUNTU_CODENAME=).*' /etc/os-release || lsb_release -cs) main" | sudo tee /etc/apt/sources.list.d/hashicorp.list

$ sudo apt update && sudo apt install terraform

--> After Install then check Terraform Version

$ terraform --version

--> Install on Windows OS 

https://releases.hashicorp.com/terraform/1.16.5/terraform_1.16.5_windows_amd64.zip

--> After Download first unzip the folder and set the environment-variables, terraform path locations and check Version.

AWS CLI :
========= 
--> Install on Ubuntu OS 

curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"
unzip awscliv2.zip
sudo ./aws/install

--> After finish this command, check Version
$ aws --verion 

--> Install on Windows OS 

msiexec.exe /i https://awscli.amazonaws.com/AWSCLIV2.msi

--> After this command run, showing on some process and check Version.
