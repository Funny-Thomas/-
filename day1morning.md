# day1 morning

## Linux

1.	ls (-al)				读取当前文件夹下所有文件（显示隐藏文件）
2.	pwd				显示当前所在目录完整路径
3.	cd 地址（没有/）			进入地址指向
4.	touch+文件名(带拓展名)		新建文件
5.	cat+文件名(带拓展名)		读取文件内容
	Esc键()				退出编辑模式
7.	:q				退出文本编辑界面
8.	:wq				写入之前输入内容并退出
9.	vim+文件名(带拓展名)		进入文本编辑界面
10.	:q!				强制退出
11.	cd ..				返回上级目录
12.	mkdir 文件夹名			新建文件夹
13.	rmdir 文件夹名			删除文件夹
14.	rm -r 文件夹名			递归删除文件夹
15.	rm -rf/				删库跑路
16.	clear或者Ctrl l			清除屏幕
17.	which 文件名			搜索路径		
18.	cp 文件名(带拓展名) 目标路径		拷贝
19.	cp ../				复制上一文件夹内的文件
20.	./				当前目录
21.	mv				剪切或者重命名
22.	ps -ef				获取进程列表
23.	kill -进程号(PID号)			结束进程
23. ps -ef | grep			管道(前者输出为后者参数)

    ## Git
1.	git init				初始化本地版本库
2.	rm -rf .git				去除master状态
3.	git status				获取库当前状态
4.	git add 文件名			加入文件从工作区进入暂存区
5.	git rm --cached 文件名		将文件从暂存区中返回
6.	git commit -m “”			提交（带上上传信息）
7.	git log				查看相关库的记录
31. git config --list			查看文件列表
git remote add origin https://github.com/Funny-luchen/-.git
    git push -u origin master
    ssh-keygen -t rsa -C "1723657812@qq.com"
