## 1.版本控制工具是什么
    软件 用来保存软件开发过程中的各个版本

## 2.为什么要用版本控制


## 第四课 git 的开发环境搭建与配置
 https://git-scm.com

依赖于 nodejs

https://nodejs.org/en

## 基础操作
    git init 初始化
    git status 查看状态

## 增加一个文件到git
    git add abc.html

## 增加当前目录到git
    git add . 

## 将缓存区代码提交到仓库
    git commit -m 'comment'

## 查看版本
    git log 

## 回到指定的版本
git checkout d243a62fa5b916b5b2ab410787490b42997cc953 

## 回到上过一个版本
    git checkout -- .

# git 的误区
    # git 与 github的区别
    # github
    # gitlab devops 企业用户比较多 。部署也比较多。。

##  git  的几个重要概念
    仓库：所有版本的代码都放在仓库里面
    分支：不同功能的代码存放的地方
    提交：每一个版本的代码

## 三区
    工作区
    暂存区
    仓库


## git clone 克隆仓库
    git clone  xxx.git 

## 查看分支
    git branch 

## 创建分支
    git checkout -b newbranch

## 合并分支
    git checkout master
    git merge newbranch master 

## 删除分支

## 权限
    private
        私有
    internal
        登陆可以看
    public
        不登录也可以看

        