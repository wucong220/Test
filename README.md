## 1.文件列表

|文件夹名称|文件夹说明|
| -------- |-------- | 
|class|用来装程序编译后的`.class`文件|
|output|用来装程序运行后输出`output.txt`文件|

|文件名称|文件说明|
| -------- |-------- | 
|ThoughtWork.java|作业程序源文件|
|build.bat|编译源文件的批处理文件|
|run.bat|运行源文件编译后得到的`.class`文件的批处理文件|
|input.txt|输入文件|
|input_eg1.txt|输入文件的样例1|
|input_eg2.txt|输入文件的样例2|

## 2.如何运行
### 2.1运行环境

java版本:1.8.0_65
在控制台输入 `java -version`查看java版本。

### 2.2 准备输入文件input.txt
1. 在当前目录下新建一个文本文件`input.txt`;
2. 在文件中输入两行数据：第一行为需要处理的文本(中间不能有换行)，第二行为文本排版的固定宽度（阿拉伯数字）。可以参考`input_eg.txt`文件
### 2.3 `ThoughtWork.java`文件编译成'.class'文件

在当前目录（`ThoughtWork.java`所在目录）下运行`build.bat`批处理文件

### 2.4 `ThoughtWork.class`文件运行

在当前目录下运行`run.bat`批处理文件。

## 3.结果显示

输出会显示在控制台上，并保存在当前目录下的`output.txt`文件中
