# git 使用
## 设置
```sh
git config --global user.name "" ## 用户名
git config --global user.email "" ### 邮箱
```

## 创建 git
`git init # 初始化`

## 添加到仓库
`git add file`

## 将文件提交到仓库
`git commit -m "提示信息"[<0;53;28M`

## 查看状态
`git status`
## 查看修改部分
`git diff file`
## 查看历史
`git log --pretty=oneline`
## 回溯
`git reset --hard commitID ## 将Head指定到某版本`
`git reset --hard HEAD^ ### 查看commit ID`
HEAD指向当前版本
git log 查看提交历史
git reflog 查看命令历史1
