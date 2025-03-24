"# test" 

cd test 
# 初始化仓库
git init

# 添加远程仓库
git remote add origin https://github.com/username/repository.git


# 确保在推送之前已经配置了 Git 用户名和邮箱,标识上传者
git config --global user.name "Your Name"
git config --global user.email "your-email@example.com"

# 添加文件到暂存区
git add .

# 提交更改
git commit -m "Initial commit"

# 推送到远程仓库
git push origin main
