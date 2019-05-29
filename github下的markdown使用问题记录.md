# github中markdown注意事项

1. 表格嵌套的话，表格之上应该有一个空行
	- 错误方式:x:
		```
		- aaa - bbb
			- ccc
				|aaa|bbb|
				|:--:|:--:|
				|111|222|
			- ddd
		```
	- 正确方式:heavy_check_mark:
		```
		- aaa - bbb
			- ccc
				
				|aaa|bbb|
				|:--:|:--:|
				|111|222|
			- ddd
		```
		
