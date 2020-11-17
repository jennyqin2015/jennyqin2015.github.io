# Welcome to Github
这篇tutorial主要介绍使用Github进行分布式版本控制的几个主要的操作。
## 创建Git Project
关于创建Git Project，有三种常见的方式。第一种是在远端，也就是github网站直接创建新的repository。在git的世界里，repository（repo）就是folder（文件夹）的另一种说法。在创建好新的repo之后，再将这个repo clone到本地（local machine）。第二种是将本地已有的文件夹，和github网站上的一个空白repo进行关联，然后再使用"git push origin master"上传本地文件到远程主机储存的项目文件夹。而第三种则是复制github其他人的repo到自己的github website，然后再通过clone保存一份本地的项目文件夹。这三种方式，无论是哪一种，项目的文件都会有两份，一份储存在github的远程主机上，而另一份则储存在我们的本地主机。在分布式版本控制系统（git）中，一般用origin来代指远程，而local代指本地主机。


```python
git remote add origin [copied web address]
git push origin master
```

### Add local repository
