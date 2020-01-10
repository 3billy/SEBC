## Database Information

```
[centos@ip-172-31-26-75 yum.repos.d]$ hostname -f
ip-172-31-26-75.ap-southeast-1.compute.internal
[centos@ip-172-31-26-75 java]$ mysql -u root -p -e "status;"
Enter password: 
--------------
mysql  Ver 14.14 Distrib 5.6.46, for Linux (x86_64) using  EditLine wrapper

Connection id:		19
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
Uptime:			2 hours 22 min 13 sec

Threads: 4  Questions: 102  Slow queries: 0  Opens: 70  Flush tables: 1  Open tables: 63  Queries per second avg: 0.011
--------------

[centos@ip-172-31-26-75 java]$ mysql -u root -p -e "show databases;"
Enter password: 
+--------------------+
| Database           |
+--------------------+
| information_schema |
| amon               |
| hue                |
| metastore          |
| mysql              |
| nav                |
| navms              |
| oozie              |
| performance_schema |
| rman               |
| scm                |
| sentry             |
+--------------------+
```
