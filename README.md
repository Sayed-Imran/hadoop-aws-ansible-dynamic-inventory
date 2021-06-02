# hadoop-aws-ansible-dynamic-inventory
### Hadoop HDFS Cluster
This ansible playbook when run provisions a Hadoop HDFS Cluster which has a Master/Name Node and two Data/Slave Node over the AWS Cloud.

### AWS
In order to run this ansible playbook you must configure the dynamic inventory i.e. via the ec2.ini and ec2.py files.
You need to mention the AWS_ACCESS_KEY and AWS_SECRET_KEY in the ec2.ini file.
Also then you need to mention the name of the key and it's path in the ansible.cfg file and also the name of the key file in the playbook of the ec2 role
