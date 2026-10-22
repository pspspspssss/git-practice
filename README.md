# Git 练习项目

用于练习 Git 本地提交与发布到 GitHub 的学习仓库。

## 项目结构

```
git-practice/
├── README.md          # 项目说明
├── .gitignore         # 忽略文件规则
└── src/
    └── Hello.java     # 示例代码
```

## 本地提交流程

```bash
# 初始化仓库
git init

# 配置身份（练习用，请替换为自己的用户名/邮箱）
git config user.name "你的用户名"
git config user.email "你的邮箱"

# 查看状态
git status

# 暂存所有改动
git add .

# 提交
git commit -m "feat: 初始化练习项目"

# 查看提交历史
git log --oneline
```
