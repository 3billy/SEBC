## Database Information

```
[centos@ip-172-31-26-75 yum.repos.d]$ hostname -f
ip-172-31-26-75.ap-southeast-1.compute.internal
[centos@ip-172-31-26-75 yum.repos.d]$ mysql -u root -p -e "status;"
Enter password: 
--------------
mysql  Ver 14.14 Distrib 5.6.46, for Linux (x86_64) using  EditLine wrapper

Connection id:		15
Current database:	
Current user:		root@localhost
SSL:			Not in use
Current pager:		stdout
Using outfile:		''
Using delimiter:	;
Server version:		5.6.46-log MySQL Community Server (GPL)
Protocol version:	10
Connection:		Localhost via UNIX socket
Server characterset:	latin1
Db     characterset:	latin1
Client characterset:	utf8
Conn.  characterset:	utf8
UNIX socket:		/var/lib/mysql/mysql.sock
Uptime:			1 hour 31 min 14 sec

Threads: 3  Questions: 77  Slow queries: 0  Opens: 70  Flush tables: 1  Open tables: 63  Queries per second avg: 0.014
--------------

[centos@ip-172-31-26-75 yum.repos.d]$ mysql -u root -p -e "show databases;"
Enter password: 
+--------------------+
| Database           |
+--------------------+
| information_schema |
| hue                |
| mysql              |
| oozie              |
| performance_schema |
| rman               |
| scm                |
| sentry             |
+--------------------+
```
