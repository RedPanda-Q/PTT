
```
python -m http.server 8090
```



Git 配置
先添加密钥
```shell
ssh-keygen -t rsa #指定rsa算法生成密钥
```
>  将公钥 `id_rsa.pub` 添加到 Github 的 SSH and GPG keys 中

```shell
ssh -T git@github.com
```
>  验证是否添加成功

```shell
git init
git remote add origin git@github.com:RedPanda-Q/PTT.git
git push -u origin main #推送
git pull origin main #拉
git status #检查冲突文件
git remote #查看远端仓库名
git remote #查看远端地址
```


```shell
git branch #查看本地仓库分支
git branch main #切换分支
git push origin master:main #推送本地master分支到远程main分支上
git branch -m master main #本地分支重命名
```
海贼王 

