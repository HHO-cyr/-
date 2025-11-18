# -
图书角管理系统 - 软件项目管理作业
# 在仓库文件夹中创建必要的文件
# 1. 创建.gitignore文件（忽略不必要的文件）
echo "node_modules/
.DS_Store
*.log
.env" > .gitignore

# 2. 更新README.md文件（用文本编辑器打开，添加项目描述）
# 内容示例：
cat > README.md << 'EOF'
# 图书角管理系统

## 项目描述
这是一个用于班级图书借阅管理的Web应用，支持图书录入、搜索、借阅和归还功能。

## 功能特性
- 图书信息管理
- 用户借阅登记  
- 借阅记录查询

## 技术栈
- 前端：HTML/CSS/JavaScript
- 后端：待定
- 数据库：待定

## 开发团队
软件项目管理课程小组
EOF

# 3. 提交初始化文件
git add .
git commit -m "init: 初始化图书角管理项目，添加README.md和.gitignore"
git push origin main
