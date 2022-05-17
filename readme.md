# Go 语言中如何开源自己写的包给别人用
https://segmentfault.com/a/1190000022770802

## 1.初始化仓库
```
git clone git@github.com:chenlongqiang/goutils.git
go mod init github.com/chenlongqiang/goutils
mkdir hash
cd hash
vi md5.go
git add .
git commit -m "Add a md5 function"
git push
```
## 2.去github上打release
