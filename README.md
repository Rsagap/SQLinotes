# SQLi Notes

## What is SQLi(SQLi)?
SQL injection is a web security vulnerability that allows an attacker to interfere with the queries that an application makes to its database. Its examples are:

1. [Retrieving hidden data](https://portswigger.net/web-security/sql-injection#retrieving-hidden-data)
2. [Subverting application logic](https://portswigger.net/web-security/sql-injection#subverting-application-logic)
3. [UNION Attacks](https://portswigger.net/web-security/sql-injection/union-attacks)
4. [Examining the database](https://portswigger.net/web-security/sql-injection/examining-the-database)
5. [Blind SQLi](https://portswigger.net/web-security/sql-injection/blind)



## Tools:
1. [SQLMap](https://github.com/sqlmapproject/sqlmap)

### Using SQLMap
1. [Cheat sheet Image](https://raw.githubusercontent.com/binexploit/SQLinotes/main/Images/sqlmap-cheatsheet.webp)



## Where to look for SQLi?
To exploit a SQL injection flaw, an attacker needs to find a parameter that the web application passes through to a database interaction. An attacker can then embed malicious SQL commands into the content of the parameter, to trick the web application to forward a malicious query to the database.





## Resources Used:
1. [Portswiggers Labs](https://portswigger.net/web-security/sql-injection)
2. [Testing for NoSQL injection wiki OWASP](https://wiki.owasp.org/index.php/Testing_for_NoSQL_injection)

