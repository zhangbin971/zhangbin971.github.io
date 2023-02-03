---
title: "linux"
date: 2021-07-24T14:58:20+08:00
draft: false
tags: ["linux"]
isCJKLanguage: true
categories: ["linux"]
---
```shell
**执行脚本  
	./shell.sh >/dev/null 2>&1   //脚本运行不输出日志
```

```shell
**sftp使用  
 	sftp -P [端口] [ip] (链接)
	
	put [本地文件的地址] [服务器上文件存储的位置] (将服务器上的文件下载到本地)
 	
	get [服务器上文件存储的位置] [本地要存储的位置] (将服务器上的文件下载到本地)
```

```shell
**scp使用
 	
	scp  -P [端口]  [ip]:[服务器上文件存储的位置] [本地要存储的位置]   (将服务器上的文件下载到本地)

	scp  -P [端口]  [本地要存储的位置]  [ip]:[服务器上文件存储的位置]  (将服务器上的文件下载到本地)
测试股
```





