# Jupter_notebook

[TOC]

### 1.概念

Jupter notebook：集文本、代码、图像、公式的展现于一体的超级web界面,支持超过40种编程语言



### 2.使用

##### 基础功能

```shell
#启动
jupyter notebook/ipython notebook
#帮助文档
? #抽象显示
?? #详细显示
```



##### 快捷键

```shell
#自动补全
tab

#编辑
enter

#执行代码
shift + enter

#执行代码并选择下一个代码块
control + enter

#执行代码并新建代码块
option + enter

#Y
coding状态

#M
markdown状态

#A
上方插入代码块

#B
下方插入代码块

#DD
删除代码块

#S
保存笔记
```



##### 魔法指令

```shell
#运行外部Python文件:%run
%run a.py 	#当前路径
%run /home/nanfengpo/Desktop/bb.py #运行其他路径

#运行linux指令:!
!echo "balala"

#查看所有变量与函数名
%who

#查看所有变量与函数名详情
%whos

#查看所有变量与函数名详情,列表形式返回
%who_is

#计算运行时间
%time 执行代码

#计算平均时间
%timeit 执行代码 

#计算多行代码平均时间
%%timeit 
执行代码1
执行代码2
执行代码3
```





