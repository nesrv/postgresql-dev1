

### PID обслуживающего процесса (отдельный для каждого клиента):


SELECT pg_backend_pid();

SELECT pg_backend_pid();


SELECT pg_terminate_backend(pid) 



### XID транзакции

SELECT pg_current_xact_id()



### PID & XID

SELECT pg_backend_pid(), pg_current_xact_id()

relation — таблицы, индексы и т. п.



Простой и современный способ:

Используйте ps -ef | grep postgresдля поиска соединения #
sudo kill -9 "#"соединения