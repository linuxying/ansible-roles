# 使用ansible来实现zabbix客户端的自动安装

|  名称 |版本信息   |
| ------------ | ------------ |
| Centos |CentOS Linux release 7.2.1511 (Core)   |
| zabbix-agent  |zabbix-agent-3.4.3-1.el7.x86_64|


# 使用方法
下载相关包文件后，修改group_vars中的变量信息为你自己实际信息
 
```
# 安装zabbix-agent
[root@ansible_server roles]# cd zabbix_agent/
[root@ansible_server zabbix_agent]# ansible-playbook install_zabbix_agent.yml
```


```
# 卸载zabbix-agent
[root@ansible_server zabbix_agent]# ansible-playbook delete_zabbix_agent.yml
```


如有错误或更好的建议，欢迎指正。