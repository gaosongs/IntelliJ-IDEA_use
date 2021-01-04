# IntelliJ IDEA如何设置新建类时，自动注释作者信息和日期时间

**本文提供两种注释风格供参考。**

 

**风格1：简约Style**

效果如下：

![img](IDEA之模板注释_作者注释模板.assets/1148440-20190401191854638-1833261117.png)

 

设置步骤：

File--> Settings--> Editor--> File and Code Templates--> Includes--> File Header--> "添加以下代码"

![img](IDEA之模板注释_作者注释模板.assets/1148440-20190401192139109-602430926.png)

![img](IDEA之模板注释_作者注释模板.assets/1148440-20190401192340230-1013397234.png)

 

添加如下代码（此处的${USER}会读取个人PC的用户名）：

```
/**
 * Created by ${USER} on ${DATE} ${TIME}
 */
```

 

如果想指定作者名称（比如：Miracle Luna），可以用以下代码：

```
/**
 * Created by Miracle Luna on ${DATE} ${TIME}
 */
```

此时效果如下：

![img](IDEA之模板注释_作者注释模板.assets/1148440-20190401192907700-1660602158.png)

 

 

 

**风格2：官方Style**

效果如下：

![img](IDEA之模板注释_作者注释模板.assets/1148440-20190401194339273-1943754501.png)

 

 

设置步骤：

File--> Settings--> Editor--> File and Code Templates--> Includes--> File Header--> "添加以下代码"

![img](IDEA之模板注释_作者注释模板.assets/1148440-20190401192139109-602430926.png)

![img](IDEA之模板注释_作者注释模板.assets/1148440-20190401194545833-2040498046.png)

 

 

添加如下代码（此处的${USER}会读取个人PC的用户名）：

```
/**
 * @Author ${USER}
 * @Date ${DATE} ${TIME}
 * @Version 1.0
 */
```

 

如果想指定作者名称（比如：Miracle Luna），可以用以下代码：

```
/**
 * @Author Miracle Luna
 * @Date ${DATE} ${TIME}
 * @Version 1.0
 */
```

此时效果如下：

![img](IDEA之模板注释_作者注释模板.assets/1148440-20190401194749834-1113753418.png)

 

 **总结**

以上是两种设置风格。喜欢哪种style？简约风？还是官方风？ ^_^