# 在Centos7上安装MySQL5.6服务

## 环境清理

这一步为可选操作，由于CentOS7可能会默认附带MariaDB，为了防止后续出现一些不必要的麻烦，这里先作一次清理工作。

查看是否存在残留的MySQL配置文件，他们可能会出现在以下目录，注意是“可能”，如果你知道其他自定义配置文件以及目录，也可以考虑备份或者清理。

```shell
rm -rf /etc/my.cnf \
	/etc/mysql/my.cnf \
	/usr/etc/my.cnf \
	/usr/my.cnf \
	~/.my.cnf
```



## 下载MySQL5.6安装包

