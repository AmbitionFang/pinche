## git

#### git命令

```git
git init     初始化
git status     文件状态查询
git add 文件名    管理文件(b --> 2)
git add . \      管理所有已初始化的文件
```

##### 	个人信息配置(用户名、邮箱，一次即可)

```
git config --global user.email"";
git config --global user.name"";
```

##### 	生成版本

```
git commit -m'v1'   生成v1版本
```

##### 	查看版本记录

```
git log
```

##### 查看版本全部记录

```
git reflog
```

2 --> b

```
git reset HEAD
```

3 --> a （回滚版本）

```
git reset --hard 版本号
```

b --> a

```
git checkout
```

3 --> b

```
git reset --mix 版本号
```



#### git分区

1工作区(working directory)

​	a已控制文件

​	b新文件/修改文件

2暂存区(staging area)

3版本库(repository)