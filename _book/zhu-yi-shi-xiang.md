# **注意事项**

> 本文涉及到的注意事项或者在学习途中遇到的问题后的解决方式

### Git修改远程仓库地址

#### 方法有三种

* 直接修改命令

```bash
$ git remote set-url origin [url]
```

* 先删除 再添加

```bash
$ git remote rm origin
$ git remote add origin [url]
```

* 直接修改config文件



