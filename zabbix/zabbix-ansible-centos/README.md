# 2- Zabbix: with this project you can install zabbix based on centos distro . If You have Centos7 , Zabbix 5 Will be installed And If you have centos8 , Zabbix 6 will be Installed . 
note: as mentioned in zabbix docs ,you can not install zabbix 6 on centos7 because  centos7 unsupported after 2024  

edit site.yml and inventory/inventory.ini with your zabbix ip server and then execute:</br>
ansible-playbook -i inventory site.yml

![ansible-zabbix](https://user-images.githubusercontent.com/42912741/224503560-ece39bf4-932d-48a6-8804-09526871ebb9.JPG)
