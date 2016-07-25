####orintmpyprogpj3
```
connection = sqlite3.connect('test.db')
cursor = connection.cursor()
cursor.execute("select * from category")
results = cursor.fetchall()
for result in results:
    field1=result
    .....
connection.close()
```

sqlite command:
```
.tables
.schema tablename
```
