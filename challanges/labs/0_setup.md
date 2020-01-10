===========Instance List================

1Challenges_billy	ec2-13-229-104-50.ap-southeast-1.compute.amazonaws.com	13.229.104.50	CentOS 7 -x86_64- - with Updates HVM-1901_01-AutogenByAWSMP-3
2Challenges_billy	ec2-18-141-57-159.ap-southeast-1.compute.amazonaws.com	18.141.57.159	CentOS 7 -x86_64- - with Updates HVM-1901_01-AutogenByAWSMP-3
3Challenges_billy	ec2-18-139-110-236.ap-southeast-1.compute.amazonaws.com	18.139.110.236	CentOS 7 -x86_64- - with Updates HVM-1901_01-AutogenByAWSMP-3

============File System Capacity ==============

[centos@ip-172-31-26-75 ~]$ df -h
Filesystem      Size  Used Avail Use% Mounted on
/dev/xvda1       30G  897M   30G   3% /
devtmpfs        7.8G     0  7.8G   0% /dev
tmpfs           7.8G     0  7.8G   0% /dev/shm
tmpfs           7.8G   17M  7.8G   1% /run
tmpfs           7.8G     0  7.8G   0% /sys/fs/cgroup
tmpfs           1.6G     0  1.6G   0% /run/user/1000

===============Yum Repository=================

[centos@ip-172-31-26-75 ~]$ sudo yum repolist enabled
Loaded plugins: fastestmirror
Determining fastest mirrors
 * base: centos.usonyx.net
 * extras: centos.usonyx.net
 * updates: centos.usonyx.net
base                                                                                                                                                                                                  | 3.6 kB  00:00:00     
extras                                                                                                                                                                                                | 2.9 kB  00:00:00     
updates                                                                                                                                                                                               | 2.9 kB  00:00:00     
(1/4): base/7/x86_64/group_gz                                                                                                                                                                         | 165 kB  00:00:00     
(2/4): extras/7/x86_64/primary_db                                                                                                                                                                     | 153 kB  00:00:00     
(3/4): base/7/x86_64/primary_db                                                                                                                                                                       | 6.0 MB  00:00:00     
(4/4): updates/7/x86_64/primary_db                                                                                                                                                                    | 5.9 MB  00:00:00     
repo id                                                                                                   repo name                                                                                                    status
base/7/x86_64                                                                                             CentOS-7 - Base                                                                                              10,097
extras/7/x86_64                                                                                           CentOS-7 - Extras                                                                                               307
updates/7/x86_64                                                                                          CentOS-7 - Updates                                                                                            1,010
repolist: 11,414

================User================

purnama:x:2700:2700::/home/purnama:/bin/bash
basuki:x:2800:2800::/home/basuki:/bin/bash

================Group==============
hackers:x:2801:
crackers:x:2802:
