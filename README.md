# sny7er-github.io


SELECT user FROM dual UNION SELECT * FROM v$version
SELECT banner FROM v$version
SELECT version FROM v$instance

SELECT banner FROM v$version WHERE banner LIKE ‘Oracle%’;
SELECT banner FROM v$version WHERE banner LIKE ‘TNS%’;
SELECT version FROM v$instance;

https://pentestmonkey.net/cheat-sheet/sql-injection/oracle-sql-injection-cheat-sheet


