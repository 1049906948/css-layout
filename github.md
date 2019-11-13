1.创建仓库

```js
git init
```

2.添加暂存库

```js
git add README.md
```

3.提交上传

```js
git commit -m "first commit"
```

4.绑定一个远程仓库。github

```js
git remote add origin https://github.com/1049906948/ck-demo.git
```

5.将本地仓库推送到远程仓库

```js
 git push -u origin master      远程组织名 推送主分支
```



****



```js
git config --global user.name "1049906948"

git config --global user.email "1049906948@qq.com"


https://1049906948.github.io/project-files/Global-traceability/
```



#### 创建ssh keys

 查看是否存在密钥ssh keys

```
cd ~/.ssh    若出现“No such file or directory”,则表示需要创建一个ssh keys。
```

##### 创建新的ssh keys

```
ssh-keygen -t rsa -C "你的邮箱名"
```

一直空格就行

######  生成了ssh keys。找到rd_rsa和id_rsa.pub  

> 把 id_rsa.pub 里的文件 放到 github 秘钥里

###### [网址推荐](https://www.cnblogs.com/sdcs/p/8270029.html)

