# DirScan

##需求
   python 2.x
   requests

一些智能错误关键字判断 和网站域名备份文件

希望多提意见:)

    croxy@Dell:~/PycharmProjects/DirScan$ python dirscan.py 
    Usage: dirscan.py [options] target
    Options:
       -h, --help            show this help message and exit
       -t THREADS_NUM, --threads=THREADS_NUM
                        Number of threads. default = 10
       -e EXT, --ext=EXT     You want to Scan WebScript. default is php
       
##v0.1

**1.增加批量扫描 把目标导入target.txt 然后自己改一下Dirscan2.py最后的ext='php'定义后缀就行**

**2. 添加错误判断如果文件返回长度为0就算不存在:( 不科学的判断方法等待改善**

##v0.2

**1. 避免备份文件过大所以使用Steam探测备份文件**

**2. 去掉长度为0即为404判断**

**3. 增加与错误页面进行相似度识别 如果相似度达到90% 即判断为404页面**

**4. 增加fast.py 使用head探测 速度飞快:)**

###感谢RickGray Ricter等人的帮助以及建议:)
