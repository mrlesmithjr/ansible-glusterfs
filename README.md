# ansible-glusterfs

An [Ansible](https://www.ansible.com) role to install/configure [GlusterFS](http://www.gluster.org/)

## Requirements

Add hard drive devices to server nodes to configure for LVM bricks and set glusterfs_config_lvm: true

## Role Variables

[defaults/main.yml](defaults/main.yml)

## Dependencies

None

## Example Playbook

    - hosts: all
      become: true
      vars:
        - config_glusterfs: true
        - config_hosts: true
        - glusterfs_config_lvm: true
        - pri_domain_name: 'test.vagrant.local'
      roles:
        - role: ansible-glusterfs
      tasks:

## License

BSD

## Author Information

Larry Smith Jr.

-   @mrlesmithjr
-   <http://everythingshouldbevirtual.com>
-   mrlesmithjr [at] gmail.com
