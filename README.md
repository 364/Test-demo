## 测试上传文件

 [编辑说明文档](https://github.com/364/Test-demo/edit/master/README.md) 
 
 查看[demo1]()  
 查看[demo2]()  
 查看[demo2]()  
 

### 记录上传过程

看了网上大神的介绍，总结整理了下上传的步骤

```markdown

1、在GitHub上New repository，然后复制地址

2、本地进入要上传的项目文件夹

2、右键打开Git Bash，没有就百度下载Git

4、配置

### 第一次使用先配置身份
git config --global user.name "名字"
git config --global user.email "邮箱"

git clone 复制的项目地址
### 把所有文件放入clone的文件夹下
cd  文件名
git add . 
git commit -m "项目信息"
git push -u origin master 
### 后面需要输入GitHub账号密码

```
### 更多Git常用命令
![Git命令](https://364.github.io/Test-demo/img/Git%E5%B8%B8%E7%94%A8%E5%91%BD%E4%BB%A4.jpg)
