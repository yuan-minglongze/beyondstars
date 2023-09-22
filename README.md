# beyondstars project

## 这是什么?

这是完全由我自主编写的中南大学2023年秋近代史纲要mooc刷课小程序.

使用python语言和selenium库,进行网页自动操作.


这是我写的第一个发布在GitHub上的开源程序,也是迄今为止我做的工程量最大的程序.耗掉了我三天时间


## 目前已实现的功能

自动打开网站,自动登录,自动检测当前学习进度,自动继续学习,自动播放视频,自动调整为2倍速,自动回答单选题,视频播放完成后自动跳转到下一小节.
直到遇到多选题或者章节测试.



## 如何使用(Windows)

**多图预警,考虑到大多数同学没什么计算机基础,我尽量将教程写得详细一些,并辅以大量图片,所以篇幅较长.有python基础的同学只要安装selenium库和edge webdriver就可以使用程序了**


因为我只用过windows系统,所以在这里只用windows写教程

### 1.安装python和edge

首先你需要准备运行环境,包括

- **python**
- **Microsoft edge(windows10,11自带浏览器)**
- **Microsoft edge webdriver**


你可以点击下面的链接自行下载
(不过edge应该都有吧,所以大多数人应该只需要下载python和webdriver)


[Python(包含python IDLE) 下载](https://www.python.org/downloads/)


[Microsoft Edge 下载](https://www.microsoft.com/zh-cn/edge/download)


[Microsoft Edge WebDriver 下载](https://developer.microsoft.com/en-us/microsoft-edge/tools/webdriver/)  (注意这个下载下来是一个压缩文件,直接解压缩就是webdriver本体,不需要安装)


或者你嫌下载速度慢,我已经把安装程序(再次强调,webdriver不需要安装,我打包的就是webdriver本身)打包为.zip了,大家直接在github下载下来解压缩再安装就可以了.

其中python的安装特别要注意,在启动python安装程序后,你会看到如下界面:

![image](https://github.com/yuan-minglongze/beyondstars/assets/129572345/4799516f-4df4-4b51-974c-f38facb667c7)

红箭头指的那个选项***一定要勾选*** ***一定要勾选*** ***一定要勾选*** (你看到的可能是3.11或者3.12),如果你忘记了勾选,请卸载掉重新安装.


### 2.安装selenium库

按 win + R ,输入cmd回车调出命令行窗口

![image](https://github.com/yuan-minglongze/beyondstars/assets/129572345/7911a5a1-07ce-4e97-9508-c8b9af2b33e3)

在命令行窗口输入 `pip install selenium` 回车就开始安装selenium库

安装完成后输入 `pip show selenium` 回车检查是否安装成功.成功后你应该看到界面如下:

![image](https://github.com/yuan-minglongze/beyondstars/assets/129572345/ded8d25e-fee5-4ae9-91d4-4bcad69fb569)





## 目前未实现的功能

- 不能避免网页检测(这个我目前的技术力应该做不了)
- 几乎不能完成多选题作答(但是ABCD全选的题目可以自动答)
- 章节测试没有实现自动(进入测试时网页会强行停止外部程序,不能完全自动化,大家直接搜答案吧)