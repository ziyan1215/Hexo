HEXO 静态博客生成

# 准备环境：
node.js
git

# 安装
git init
git remote add origin git@github.com:ziyan1215/Hexo.git
git pull origin master
npm install -g hexo-cli

npm install

安装next主题（可以省略）
git clone https://github.com/iissnan/hexo-theme-next themes/next


# 启动
hexo g
hexo server

# 访问：
http://localhost:4000/

## 已集成hexo-admin
http://localhost:4000/admin/login/