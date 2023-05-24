# Ansible
in this repository we are going to use ansible to manage or install packge or services . 

# 1- Timezone: this Folder correct Time Zone of your linux Server(Tehran TimeZone) . for your Enviroment Change inventory file with your IP Servers And Execute :
 #ansible-playbook roles/tasks/playbook.yml -i inventory
 
 
![timezonepic](https://user-images.githubusercontent.com/42912741/222965252-7a29f14e-af00-4559-89c2-c41dd7b5b257.JPG)

# 2- Zabbix: with this project you can install zabbix based on centos distro . If You have Centos7 , Zabbix 5 Will be installed And If you have centos8 , Zabbix 6 will be Installed . 
note: as mentioned in zabbix docs ,you can not install zabbix 6 on centos7 because  centos7 unsupported after 2024  

![ansible-zabbix](https://user-images.githubusercontent.com/42912741/224503583-bdd43a04-458d-4e33-83fc-83dd6ca6e9f1.JPG)

# 3 Install zabbix proxy with ansible:<br>
os:centos8 <br>
change your inventory file and then execute:<br>
#ansible-playbook site.yml


![zabbixproxy-withansible](https://user-images.githubusercontent.com/42912741/235248694-ea0a5b91-462a-468d-bf6b-8db832e56cf4.JPG)

# 4 create hostgroup in zabbix with ansible <br>

os :ubuntu 20.04 <br>
ansible version : 2.12 <br>
python version: 3.9 <br>

note: for using hostgroup module , the version of ansible is important ! this module does not work with ansible 2.9 or before <br>

![zabbix-hostgroup](https://github.com/amirajoodani/Ansible/assets/42912741/5f129165-7408-4d56-96c6-8da5a0e851fb)


