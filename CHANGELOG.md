commit 2c77877da17a150e4195f4fbe1f7534f7ae56e62
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Jul 31 14:05:34 2020 -0400

    Disabled Debian8 testing

commit f609973612e0040d3280fad0903b00c95094cf89
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Jul 31 13:40:10 2020 -0400

    Fixing CentOS8

commit fe1a3ac1be2320713c718bf0f31dfb8cd4c429ed
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Jul 31 13:09:55 2020 -0400

    Fixing Debian repo issues

commit 46de2aa0cb8fd92cbabfd59f83267ced6265b4a2
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Jul 31 00:41:43 2020 -0400

    Fixed Debian repo

commit c43951073cb9858eafaad1530bdd64d9aa98dac4
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Jul 31 00:33:40 2020 -0400

    removed glustereventsd service

commit 24b460cf634953ad324ad79629a53d3576f65062
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Jul 31 00:20:12 2020 -0400

    Fixing Debian pre-reqs

commit ff39a565c74657478080100d8665dd97560b2007
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Jul 31 00:10:23 2020 -0400

    Added pre-req gnupg

commit 435e8ad45431858bcf7d7305028a96125f07071c
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Jul 30 23:45:46 2020 -0400

    Changed replication interface for Molecule testing

commit fbe5a1807a39e8129858dd9e2be1e565876ef00e
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Jul 30 23:39:52 2020 -0400

    Changed default Ansible group

commit 2fd09b9bb1647d4afcfa0f2ecd2b345434a6765e
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Jul 30 23:39:40 2020 -0400

    Fixed linting

commit 03005f66cbece0fa7d171af748d150d7bc90c6b9
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Jul 30 23:30:35 2020 -0400

    Fixed linting

commit 3dd41048c871272a0d503e1b0473bd634107f644
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Jul 30 23:25:58 2020 -0400

    Added new files based on Cookiecutter template

commit d2d5fffa089ea59bf7035b2b4e95e00b5978171d
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Jul 30 23:24:49 2020 -0400

    Refactored based on a more simplified install
    
    - The install is a lot cleaner now and simplified

commit c7f953996b0d762d754e74a43bb967dfc304fcb5
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Jul 30 23:20:31 2020 -0400

    Deleted tasks that should not be in this role
    
    - We should manage LVM outside of this role
    - We should manage GlusterFS clients outside of this role
    - Refactored the remaining tasks which should be in this role

commit 75d2451403a885ff468c94f8892246079978693a
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Sep 5 19:30:32 2019 -0400

    Fixing conditional checks

commit aeee21c541af151a444980d7547f58fca62135b5
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sat Aug 31 00:52:55 2019 -0400

    Added new service info for Debian Buster
    
    - This has only been experienced on Debian Buster as of now. This issue
    was original raised via https://github.com/mrlesmithjr/ansible-rpi-k8s-cluster/issues/21

commit 00fe89b4645aa07fcabf03eddb1228b94e37e7fc
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Jun 13 22:23:26 2018 -0400

    Resolves issue #1

commit 4594e86ba19aa8831b8ef1e213117175848a01bf
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Feb 7 10:48:15 2018 -0500

    Updated Ansible Galaxy meta info

commit 0152b81965fe4f689034ac5e132cc9f469ffff10
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Feb 7 10:47:41 2018 -0500

    Fixed Debian repo

commit 1ff9a27661a71f1a2bbaf28aecfa80e5ccea4d28
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Feb 7 10:12:26 2018 -0500

    Updated repo info

commit 889f515086787b89a9153ee0dc86c92b5c0904cb
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Feb 7 10:12:18 2018 -0500

    Updated Ansible Galaxy meta info

commit 1472839099124c851b097dc17769ec2efcc75476
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Feb 7 10:12:06 2018 -0500

    Cleaned up default vars

commit ba0be4914cdd5928eb4f264e44bd3f9f057146f5
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Feb 7 10:11:49 2018 -0500

    Fixed Ansible group logic and added ability to force create root bricks

commit c2d63d9cddf1557556daebd2b4ab3caec076eb99
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Feb 7 10:11:20 2018 -0500

    Fixed Ansible group logic. And fixed Ubuntu repo key

commit bbf3b0eae1b17983a2b56da64817e7bd2cbc38e8
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Feb 7 10:10:50 2018 -0500

    Added example playbook

commit 8326b466afd3916473d551dee12f874b357bc7f2
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Feb 7 09:31:10 2018 -0500

    Fixed Ubuntu repo

commit 19608547d6c19e06e1023ff58e1c66b522c68a02
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Feb 7 09:08:29 2018 -0500

    Removed etc/hosts tasks.
    
    Name resolution should be resolved with etc-hosts role or a functional
    DNS infra.

commit 21449bc70867ce52be2f59eb71567ba1482256a9
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Feb 7 08:43:09 2018 -0500

    Cleaned up formatting of vars and layout

commit a41dbf02f9fda527de2a981ef2064e0c7ed01811
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sat Mar 18 00:10:13 2017 -0400

    Fixed ansible-lint issues
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit c0855951de05e2fd5fa7626af5e4e9d4ffae7ce7
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Mar 17 20:00:59 2017 -0400

    Added changed_when: false for task to check for existing volumes
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit e97f69eac48ddceee38227d9668d7fbe669a3757
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Mar 17 19:18:25 2017 -0400

    Fixed issue with running in check mode during check for existing volumes
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit 65a7fd10eb0eb8367828b7727880b9f8c3f6cbed
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Mar 17 19:11:19 2017 -0400

    Fixed typo
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit e6c9736952d052ba714235e84a38a7c16968060e
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Mar 17 19:10:11 2017 -0400

    Added task to query existing volumes and only create them when not found currently. This is to work around the issue of when the task to create a new volume already finds the volume exists
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit d326ed2852b8fa1898c4ac1287c532d6d0b8a77b
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Sat Mar 26 13:19:37 2016 -0400

    Added var to determine how much to grow volume by
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.coml>

commit 0e860009cc79092afe28d82774730dcde07a1d8b
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Sat Mar 26 00:58:20 2016 -0400

    Updated role info
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.coml>

commit 25cfab2a16cff06245ee1bf70216a086fc94ec57
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Sat Mar 26 00:57:42 2016 -0400

    Reorganized tasks
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.coml>

commit 513389d8fc0a3741d67f7e00643c535479d8e82f
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Sat Mar 26 00:57:23 2016 -0400

    Updated vars
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.coml>

commit 8a3dc5dec919540024ba05457632fc1bf2749260
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Sat Mar 26 00:57:10 2016 -0400

    Added initial phase of resizing LVM
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.coml>

commit 64d65a17b8804ae34a70569b0961e90e73e03c9d
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Sat Mar 26 00:56:36 2016 -0400

    Made brick mountpoints hidden
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.coml>

commit 59d991d86ccc3855747976f1cd216f3ae0495293
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Wed Mar 23 22:46:20 2016 -0400

    Fixed mount options
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.coml>

commit b4ee7e2f33bd69c7927550efb5c609d7c887085d
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Wed Mar 23 19:04:13 2016 -0400

    Updated mount options
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.coml>

commit 5e780c8d369a153adc43f0556731fa5e8bdee879
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Wed Mar 23 16:23:10 2016 -0400

    Added tasks to join arbiter nodes
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.coml>

commit 9296cc980eb4b0e88c87cad1cfc51dd112486f87
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Wed Mar 23 16:22:53 2016 -0400

    Reorganized tasks
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.coml>

commit 6fe540946c52ac2215a816baf2a48d0d45342f56
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Wed Mar 23 16:22:22 2016 -0400

    Updated vars for arbiter nodes
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.coml>

commit a3c40c724a44473bb63ceda49148e040e405f6ef
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Wed Mar 23 16:22:00 2016 -0400

    Updated Role info
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.coml>

commit a8519a13dfb903357945b5f672fbbc0fce16608d
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Tue Mar 22 23:52:53 2016 -0400

    Cleaned up join cluster task,
    
    added options for gluster mounts
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.coml>

commit cba79c9f5a001fab282b2f5d46233771ffd33eb4
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Wed Mar 16 20:34:00 2016 -0400

    Working through HA-Setup of Cacti
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.coml>

commit 63053e78b6ac6e0c11602216947361ae4f77c7fc
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Sat Mar 12 01:50:00 2016 -0500

    Fixed hosts file template and added Debian repo info
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.coml>

commit fce207e30e42608c29f28f03bb7dde901983f9f4
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Fri Mar 11 23:34:21 2016 -0500

    Complete rewrote role
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.coml>

commit 357f2e5ab7532f596a284949cd0d1bf7a05fc52d
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Fri Mar 11 16:45:23 2016 -0500

    Updated all tasks for role
    
    Cleaned up tasks....reorganized variables and etc.
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.coml>

commit 82cfd4169bf36ae9ac9ba5a4d45ff34c6b6e9216
Author: Larry Smith Jr <larry.e.smith.jr@gmail.com>
Date:   Thu Aug 13 00:25:55 2015 -0400

    changed ansible_fqdn to ansible_hostname

commit 10d5c91e0d52fa5f1873c3dd1e270301b8ede035
Author: Larry Smith Jr <larry.e.smith.jr@gmail.com>
Date:   Thu Aug 13 00:15:42 2015 -0400

    cleaned up vars

commit df0c3dc1b069cc55998b1f33e05ef127e8e35be0
Author: Larry Smith Jr <larry.e.smith.jr@gmail.com>
Date:   Thu Aug 13 00:11:26 2015 -0400

    fixed typo

commit a4129c6859c043df9326b5fb52936f452c0985b0
Author: Larry Smith Jr <larry.e.smith.jr@gmail.com>
Date:   Thu Aug 13 00:09:06 2015 -0400

    changed cluster and replica method:

commit f79cb5a72f033936e185eeda4d8ee04574f2381b
Author: Larry Smith Jr <larry.e.smith.jr@gmail.com>
Date:   Wed Aug 12 23:58:34 2015 -0400

    added update etc/hosts task

commit 3ac0ae516b1cec860ff1e3d1bbb679652a792df7
Author: Larry Smith Jr <larry.e.smith.jr@gmail.com>
Date:   Wed Aug 12 23:58:16 2015 -0400

    updated vars,meta and moved etc/hosts task by itself

commit 5ae5c6b42aedee60621068e8c50401fff1d461dc
Author: Larry Smith Jr <larry.e.smith.jr@gmail.com>
Date:   Wed Aug 12 22:08:15 2015 -0400

    added lvm tasks,updated vars, updated meta

commit e2b5fac3f958ec6ebeedd959b470957fabb9b385
Author: Larry Smith Jr <larry.e.smith.jr@gmail.com>
Date:   Wed Aug 12 21:53:58 2015 -0400

    updated meta

commit aba0219c2d6f560eea126167fa5aaf386930c42d
Author: Larry Smith Jr <larry.e.smith.jr@gmail.com>
Date:   Wed Aug 12 21:51:22 2015 -0400

    first commit
