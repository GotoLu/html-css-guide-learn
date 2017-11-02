### CSS书写规范
```
书写格式

选择器与大括号之间保留一个空格；
分号之后保留一个空格；
逗号之后保留一个空格；
所有规则需换行；
多组选择器之间需换行。
```

不推荐：
```
main{
	display:inline-block;
}
h1,h2,h3{
	margin:0;
	background-color:rgba(0,0,0,.5);
}
```
推荐：
```
main {
	display: inline-block;
}
h1,
h2,
h3 {
	margin: 0;
	background-color: rgba(0, 0, 0, .5);
}
```