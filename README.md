# burpExtenderSqlmapAction
通过Jython编写burp的插件，增加右键action可直接发送数据包到本地的sqlmap，获得注入点会有警报声。
由于在win下sqlmapapi.py无法使用，通过此种方法直接执行sqlmap命令。

预期后期版本重定向输出到burp识别数据，来添加最终结果到scan栏。
