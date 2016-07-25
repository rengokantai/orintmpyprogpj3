####orintmpyprogpj3
```
connection = sqlite3.connect('test.db')
cursor = connection.cursor()
cursor.execute("select * from category")
