# deploy-hadoop-exporter
Ansible deploy hadoop-exporter

### 使用
    编译 hadoop_exporter , 拷贝到 roles/hadoop_exporter/files/hadoop_exporter
    根据部署环境修改 hosts/hadoop-exporter.ini
    执行部署 ansible-playbook -i hosts/hadoop-exporter.ini 01-hadoop-exporter.yml
    
Ansible deploy hbase-exporter

### 使用
    编译 hbase_exporter , 拷贝到 roles/hbase_exporter/files/hbase_exporter
    根据部署环境修改 hosts/hbaser-exporter.ini
    执行部署 ansible-playbook -i hosts/hbase-exporter.ini 02-hbase-exporter.yml
