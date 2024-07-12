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



















































































