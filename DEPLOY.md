# 🚀 网站部署指南

你的个人主页已经准备好部署！手机和电脑都能访问。

## 方法1：使用Vercel（推荐，最简单）

### 步骤1：注册Vercel账号
1. 访问 [vercel.com](https://vercel.com)
2. 点击 "Sign Up" 使用GitHub账号登录
3. 授权Vercel访问你的GitHub

### 步骤2：安装Vercel CLI
```bash
npm install -g vercel
```

### 步骤3：部署网站
```bash
# 进入项目目录
cd zhengzhikang-website

# 登录Vercel
vercel login

# 部署网站
vercel --prod
```

### 步骤4：获取链接
部署完成后，Vercel会给你一个类似这样的链接：
`https://zhengzhikang.vercel.app`

## 方法2：使用GitHub Pages

### 步骤1：创建GitHub仓库
1. 登录 [github.com](https://github.com)
2. 点击 "New repository"
3. 仓库名称：`zhengzhikang-homepage`
4. 选择 "Public"
5. 点击 "Create repository"

### 步骤2：上传文件
```bash
# 进入项目目录
cd zhengzhikang-website

# 初始化Git仓库
git init

# 添加远程仓库（替换为你的仓库URL）
git remote add origin https://github.com/你的用户名/zhengzhikang-homepage.git

# 添加文件
git add .
git commit -m "Initial commit - 郑志康个人主页"

# 推送到GitHub
git push -u origin main
```

### 步骤3：启用GitHub Pages
1. 进入仓库的 "Settings"
2. 点击 "Pages"
3. 选择 "main" 分支
4. 点击 "Save"

### 步骤4：访问网站
几分钟后，你的网站将在以下地址可用：
`https://你的用户名.github.io/zhengzhikang-homepage`

## 方法3：手动上传到免费主机

### 使用Netlify
1. 访问 [netlify.com](https://netlify.com)
2. 注册账号
3. 点击 "New site from Git"
4. 连接你的GitHub仓库
5. 选择你的仓库
6. 点击 "Deploy site"

## 📱 手机访问优化

你的网站已经针对移动设备进行了优化：
- ✅ 响应式设计
- ✅ 触摸友好的按钮
- ✅ 适合小屏幕的字体大小
- ✅ 优化的导航菜单

## 🔗 分享你的网站

部署完成后，你可以：
1. 在微信中分享链接
2. 添加到手机主屏幕（PWA效果）
3. 通过二维码分享
4. 在社交媒体上发布

## 🛠 需要帮助？

如果你在部署过程中遇到任何问题，请告诉我：
- 你选择哪种部署方式
- 遇到的具体错误信息
- 你的技术熟悉程度

我会为你提供更详细的指导！

---

**网站特色** ✨
- 高级绿色橙色配色方案
- 响应式设计，手机电脑都适配
- 流畅的动画效果
- 完整的个人介绍和使命展示
- 现代化UI设计