Hadoop ansible-playbooks
=========================

Installs and configure Hadoop system in a cluster of nodes.
How to use it:

In the "Worker Nodes"
- include: hadoop/tasks/hadoop-wn.yml hadoop_master=<MASTER_NODE_NAME_OR_IP>

In the "Manager Node"
- include: hadoop/tasks/hadoop-master.yml hadoop_master=<MASTER_NODE_NAME_OR_IP>
