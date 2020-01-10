## List Repository

```
[centos@ip-172-31-25-26 ~]$ ls -ltr /etc/yum.repos.d/
total 36
-rw-r--r--. 1 root   root   5701 Nov 23  2018 CentOS-Vault.repo
-rw-r--r--. 1 root   root   1331 Nov 23  2018 CentOS-Sources.repo
-rw-r--r--. 1 root   root    630 Nov 23  2018 CentOS-Media.repo
-rw-r--r--. 1 root   root    314 Nov 23  2018 CentOS-fasttrack.repo
-rw-r--r--. 1 root   root    649 Nov 23  2018 CentOS-Debuginfo.repo
-rw-r--r--. 1 root   root   1309 Nov 23  2018 CentOS-CR.repo
-rw-r--r--. 1 root   root   1664 Nov 23  2018 CentOS-Base.repo
-rw-r--r--. 1 centos centos  290 Jan 10 11:15 cloudera-manager.repo

```


## Write Database

```
[centos@ip-172-31-25-26 ~]$ sudo /usr/share/cmf/schema/scm_prepare_database.sh mysql scm scm -h 172.31.26.75
Enter SCM password: 
JAVA_HOME=/usr/java/jdk1.7.0_67-cloudera
Verifying that we can write to /etc/cloudera-scm-server
Creating SCM configuration file in /etc/cloudera-scm-server
Executing:  /usr/java/jdk1.7.0_67-cloudera/bin/java -cp /usr/share/java/mysql-connector-java.jar:/usr/share/java/oracle-connector-java.jar:/usr/share/java/postgresql-connector-java.jar:/usr/share/cmf/schema/../lib/* com.cloudera.enterprise.dbutil.DbCommandExecutor /etc/cloudera-scm-server/db.properties com.cloudera.cmf.db.
[                          main] DbCommandExecutor              INFO  Successfully connected to database.
All done, your SCM database is configured correctly!
```