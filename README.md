Role Name
=========

Installs GlusterFS http://www.gluster.org/ (configures and creates cluster)

Requirements
------------

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

Role Variables
--------------

````
cluster_hosts: 'gluster-n1,gluster-n2,gluster-n3'  #defines the hosts to join cluster...define here or in group_vars/group
config_glusterfs: false  #defines if glusterfs should be configured
create_gluster_bricks:
  - name: scripts
    owner: root
    group: root
    replicas: 2
  - name: webs
    owner: root
    group: root
    replicas: 2
glusterfs_brick_dir: /mnt/gluster  #defines the mountpoint for gluster bricks and volumes to be created
glusterfs_client: false  #defines if host is a glusterfs client
glusterfs_repl_int: eth0  #defines interface to configure for glusterfs replication...define here or in group_vars/group
glusterfs_server: false  #defines if host is a glusterfs server
glusterfs_version: 3.5
server_group: glusterfs-nodes  #defines the hosts inventory group to configure...define here or in group_vars/group
````

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: glusterfs-nodes
      roles:
         - { role: mrlesmithjr.glusterfs }

License
-------

BSD

Author Information
------------------

Larry Smith Jr.
- @mrlesmithjr
- http://everythingshouldbevirtual.com
- mrlesmithjr [at] gmail.com
