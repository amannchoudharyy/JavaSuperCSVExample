

JavaSuperCSVExample
===================

SuperCSV是一个速度奇快、免费跨平台的 CVS 格式数据的读写库，可以方便的处理对象、Map、列表的读写操作，以及自动化的类型转换和数据检查功能。

http://supercsv.sourceforge.net/

http://super-csv.github.io/super-csv/index.html

https://mvnrepository.com/artifact/net.sf.supercsv

https://stackoverflow.com/questions/11678238/using-csvbeanreader-to-read-a-csv-file-with-a-variable-number-of-columns


### 表格数据

```
6524,1,1984/10/30,4000066
6525,2,1984/10/30,4000067
6526,3,1984/10/30,4000068
6527,4,1984/10/30,4000069
6528,5,1984/10/30,4000070
6529,6,1984/10/30,4000071
6530,7,1984/10/30,4000072
6531,8,1984/10/30,4000073
6532,9,1984/10/30,4000074
6533,10,1984/10/30,4000075
```

```
北京,上海,深圳,广州

6524,1,1984/10/30,4000066
6525,2,1984/10/30,4000067
6526,3,1984/10/30,4000068
6527,4,1984/10/30,4000069
6528,5,1984/10/30,4000070
6529,6,1984/10/30,4000071
6530,7,1984/10/30,4000072
6531,8,1984/10/30,4000073,90908890
6532,9,1984/10/30,4000074
6533,10,1984/10/30,4000075
```

### 输出log
6524	1	Tue Oct 30 00:00:00 CST 1984	4000066

6525	2	Tue Oct 30 00:00:00 CST 1984	4000067

6526	3	Tue Oct 30 00:00:00 CST 1984	4000068

6527	4	Tue Oct 30 00:00:00 CST 1984	4000069

6528	5	Tue Oct 30 00:00:00 CST 1984	4000070

6529	6	Tue Oct 30 00:00:00 CST 1984	4000071

6530	7	Tue Oct 30 00:00:00 CST 1984	4000072

6531	8	Tue Oct 30 00:00:00 CST 1984	4000073

6532	9	Tue Oct 30 00:00:00 CST 1984	4000074

6533	10	Tue Oct 30 00:00:00 CST 1984	4000075


北京	上海	深圳	广州

6524	1	1984/10/30	4000066

6525	2	1984/10/30	4000067

6526	3	1984/10/30	4000068

6527	4	1984/10/30	4000069

6528	5	1984/10/30	4000070

6529	6	1984/10/30	4000071

6530	7	1984/10/30	4000072

6531	8	1984/10/30	4000073 90908890

6532	9	1984/10/30	4000074

6533	10	1984/10/30	4000075

lineNum=10
rowNum=5

# 作者联系方式
  QQ:1196681436
  Weibo:http://www.weibo.com/u/1693069642

欢迎提出意见，提交代 
