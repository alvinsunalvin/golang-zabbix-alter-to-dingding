# golang-zabbix-alter-to-dingding
zabbix报警到钉钉

更多详情：http://www.qiansw.com/golang-zabbix-alter-to-dingding.html


## 变更记录
	2016-08-01 21:22		增加了对xml源消息的支持，防止json格式的消息中有引号造成消息失败的问题。
	2017-01-09 13:08		增加了对消息内 url 字段支持。
	2017-09-19 13:55		完善了log，可以记录到文件；支持了 zabbix 3.4 中恢复消息状态 “RESOLVED”。

##### 未实现的功能
- 禁止要求非空参数的提醒