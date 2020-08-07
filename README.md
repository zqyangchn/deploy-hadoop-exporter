# deploy-hadoop-exporter
Ansible deploy hadoop-exporter

### 使用
    编译 hadoop_exporter , 拷贝到 roles/hadoop_exporter/files/hadoop_exporter
    根据部署环境修改 hosts/hadoop-exporter.ini
    执行部署 ansible-playbook -i hosts/hadoop-exporter.ini 01-hadoop-exporter.yml
