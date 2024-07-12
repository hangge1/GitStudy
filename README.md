# GitStudy
My experience of restuding git command etc.



**Git诞生原因：**

1、Linus在1991年创建开源Linux，刚开始世界各地通过diff方式，发给Linus本人手工方式合并

2、但是随着规模扩大，很难手工管理。2002年，BitMover公司处于人道主义精神，授权Linux社区免费使用此版本管理系统

3、由于Linus社区有人试图破解BitKeeper的协议，被公司收回了免费使用权

4、Linux花了两周用c写了第一版的分布式版本控制系统，就是Git

5、2008年，Github网站上我，它为开源项目免费提供Git存储！



**集中式和分布式：**

区别：

1、网络敏感性

2、版本库安全性

3、分支支持模式



**创建版本库：**

```bash
mkdir learngit
cd learngit
git init
```

**文件添加到版本库：**

注：

1、所有版本控制系统，只能跟踪文本文件改动，二进制文件是没办法跟踪变化

2、建议不要用Windows的记事本编写文本

```bash
git add xxx.txt
git commit -m "wrote a readme file"
```



**查询仓库状态：**

```
git status
```



**查询当前工作目录某文件和版本库对比的修改内容：**

```
git diff [filename]
```



**查询提交记录：**

```
git log
git log --pretty=oneline

//默认显示从最近到最远的日志记录
git log
commit 7fb71cb4b3bad42dfca6760f1c726ec160de463a (HEAD -> main)
Author: hangdada <824362330@qq.com>
Date:   Fri Jul 12 17:55:03 2024 +0800

    Git add distributed

commit d2ce32f101ce47c7236e473d8027bca4ffa4cd7c
Author: hangdada <824362330@qq.com>
Date:   Fri Jul 12 17:52:08 2024 +0800

    add diff to readme.txt

//如果觉得信息太多，可加上 --pretty=oneline参数
git log --pretty=oneline
7fb71cb4b3bad42dfca6760f1c726ec160de463a (HEAD -> main) Git add distributed
d2ce32f101ce47c7236e473d8027bca4ffa4cd7c add diff to readme.txt
e1c65d87b6d27bff8729556b51e3bac1edfddd0f add readme file.txt
af7fb6de80b6e3a44e32bcca0092ab945d550e1c (origin/main, origin/HEAD) Initial commit
```



**版本回退：**









































































