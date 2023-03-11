# Ansible
in this repository we are going to use ansible to manage or install packge or services . 

# 1- Timezone: this Folder correct Time Zone of your linux Server(Tehran TimeZone) . for your Enviroment Change inventory file with your IP Servers And Execute :
 #ansible-playbook roles/tasks/playbook.yml -i inventory
 
 
![timezonepic](https://user-images.githubusercontent.com/42912741/222965252-7a29f14e-af00-4559-89c2-c41dd7b5b257.JPG)

# 2- Zabbix: with this project you can install zabbix based on centos distro . If You have Centos7 , Zabbix 5 Will be installed And If you have centos8 , Zabbix 6 will be Installed . 
# note: as mentioned in zabbix docs ,you can not install zabbix 6 on centos7 because  centos7 unsupported after 2024  
