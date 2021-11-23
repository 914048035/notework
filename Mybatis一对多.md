​​​​​​![在这里插入图片描述](https://img-blog.csdnimg.cn/feacf2dbb4304c77bc72c9b506797b9e.png)
一对多：==集合 #9C27B0==，一个老师有多个学生

多对一：==关联 #9C27B0==，多个学生关联一个老师

==student #F44336==
![enter description here](./images/1637652532910.png)

<font color="red">teacher</font>
![enter description here](./images/1637652640826.png)

sql语句查询学生和关联的老师

``` sql
select sid, sname,tname from mybatis_study.student s,mybatis_study.teacher t where s.tid=t.tid
```
![enter description here](./images/1637652790970.png)
