# sql-injection
basic information on this attack

SQL injection is a code injection technique, used to attack data-driven applications, in which malicious SQL statements are inserted into an entry field for execution (e.g. to dump the database contents to the attacker).[1] SQL injection exploit a security vulnerability in an application's software, for example, when user input is either incorrectly filtered for string literal escape characters embedded in SQL statements or user input is not strongly typed and unexpectedly executed. SQL injection is mostly known as an attack vector for websites but can be used to attack any type of SQL database. @wikipedia https://en.wikipedia.org/wiki/SQL_injection 

The working of injection is like this
Normaly an sql statement inserted starts with ' or " . So when the userinput field say username is saved to a variable it is saved as var='' so if the sql statement we insert is like this-  ' or 1=1 --  so the 

There are few steps while doing an injection
Step 1: Injection Detection
Step 2: DBMS Identification
Step 3: Injection Types
Step 4: Injection Techniques
Step 5: Attack Queries

Sql injection is of two types
1) In-band SQLi (Classic SQLi)
2) Inferential SQLi and 
3) Out-of-band SQLi.

