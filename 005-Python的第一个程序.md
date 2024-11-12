# Python的第一个程序

## 控制台方式

打开CMD命令行，然后输入`python`命令进入Python控制台，然后输入语句`print("hello world!")`。


## 文件方式

这是初学者一开始接触的方式，它的优势在于可以快速执行并体验，但是缺点命令行只能执行一条语句。而我们的业务是许许多多的语句组合在一起的，所以我们可以把语句写入到一个文件中，如果执行这个文件的话，就可以执行多条语句了。所以就有了`.py`后缀格式的文件。

假设我们的代码都存放到目录：`E:\Python_codes\`，首先进入这个目录我们新建一个目录`hello-world`并进入这个目录，在这个目录下新建一个文本文件，并且后缀名一同修改：`helloworld.py`，最后用记事本打开这个文件：

`E:\Python_codes\hello-world\helloworld.py`

```py
print("Hello World")
```

在`E:\Python_codes\hello-world\`文件夹打开CMD控制台，输入`python helloworld.py`。

## IDLE自带编辑器

## 开发注意事项

1. Python源文件通常以`.py`为扩展名（规范），但这不是必须的；
2. Python程序语句默认情况下是顺序执行；
3. Python是区分大小写的
4. Python程序是由一条一条语句构成的，每条语句最后不需要以";"（注意是输入法为英文状态的）结束，但是如果带上";"也不会报错，但建议不带";"（规范）
