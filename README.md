Hadoop Role
=========

This role configures hadoop over your master slave cluster. You just need to add the inventory file with the group name 'master' and 'slave'. First, it makes the changes required in the core-site and the hdfs-site files in the master as well as the slave. Then, formats the name node and starts the services of name node as well as the data node. 

Requirements
------------

You need to have the hadoop sofware and the jdk installed in the datanode as well as the master node. 
