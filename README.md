"# test" 

# 初始化仓库
git init

# 添加远程仓库 （如果已有仓库则不需要）
git remote add origin https://github.com/username/repository.git
# sourceforge同样
git remote add origin <SourceForge 仓库地址>

# 确保在推送之前已经配置了 Git 用户名,标识上传者
git config --global user.name "Your Name"
# 邮箱
git config --global user.email "your-email@example.com"

# 添加文件到暂存区
git add .

# 提交更改
git commit -m "commit describe"

# 推送到远程仓库 
git push origin main

# 后续更新
git add <filename> 或 .
#
git commit -m "commit describe"
#
git push


