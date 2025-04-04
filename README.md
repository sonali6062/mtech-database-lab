# mtech-database-lab
chapter8
Auditing models

SQL> CREATE USER audit_user IDENTIFIED BY audit123;

User created.

SQL>  GRANT CONNECT,RESOURCE TO audit_user;

Grant succeeded.

SQL> GRANT CREATE TABLE,CREATE SEQUENCE,CREATE TRIGGER TO audit_user;

Grant succeeded.

SQL> GRANT CREATE TABLE TO audit_user;

Grant succeeded.

SQL> GRANT CREATE VIEW TO audit_user;

Grant succeeded.
