#  python 连接mysql
# python mysql 数据库连接：pymysql

1.安装module: pymysql: `pip install PyMySQL`  

2.连接数据库：
```
#!/usr/bin/python3

import pymysql

# 打开数据库连接
db = pymysql.connect("localhost","用户名","密码","数据库名" )

# 使用 cursor() 方法创建一个游标对象 cursor
cursor = db.cursor()

# 使用 execute()  方法执行 SQL 查询
cursor.execute("SELECT VERSION()")

# 使用 fetchone() 方法获取单条数据.
data = cursor.fetchone()

print ("Database version : %s " % data)

# 关闭数据库连接
db.close()


```

