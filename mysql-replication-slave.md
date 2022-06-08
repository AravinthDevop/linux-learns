## mysql replication slave configuration



common errors

1146 

check slave status 
 set Slave_IO_Running and Slave_SQL_Running change no to yes using this command 
 SET GLOBAL SQL_SLAVE_SKIP_COUNTER = 1;
