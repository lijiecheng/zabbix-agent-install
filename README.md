使用方法：

  1、进入到roles目录下安装ansible, rpm -ivh ansible/*.rpm  --force --nodeps;

  2、在hosts文件中填写上需要安装的节点ip和密码;
  
  3、然后执行ansible-playbook -i hosts zabbix.yml
