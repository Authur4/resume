# 刘逸凡 · 个人简历网站

交互式杂志编辑风个人简历，专为内容运营/社区运营岗位打造。

## 🔗 在线预览

部署到 GitHub Pages 后，链接格式：
`https://你的GitHub用户名.github.io/resume`

## 📁 文件说明

| 文件 | 说明 |
|------|------|
| `index.html` | 简历网站（单文件，浏览器直接打开） |
| `刘逸凡_简历.docx` | Word 文档简历（可下载发给 HR） |

## 🚀 如何部署到 GitHub Pages（获得公网链接）

### 第一步：创建 GitHub 仓库
1. 打开 https://github.com 并登录
2. 点击右上角 **+** → **New repository**
3. 仓库名填 `resume`（或其他你喜欢的名字）
4. 设置为 **Public**（公开）
5. 不要勾选任何初始化选项，点 **Create repository**

### 第二步：推送文件
创建仓库后会看到上传指引，在终端执行：

```bash
cd resume-site
git init
git add index.html
git commit -m "简历网站"
git branch -M main
git remote add origin https://github.com/你的用户名/resume.git
git push -u origin main
```

### 第三步：开启 GitHub Pages
1. 进入仓库 → **Settings** → **Pages**
2. **Source** 选 `Deploy from a branch`
3. **Branch** 选 `main`，文件夹选 `/ (root)`
4. 点击 **Save**
5. 等待 1-2 分钟，页面顶部会显示你的链接

### 第四步：分享
把链接 `https://你的用户名.github.io/resume` 发给 HR，点开即看！

---

## 💡 网站特点

- 📱 响应式设计，手机/平板/桌面都能看
- 🎨 杂志编辑风，暖色调 + 卡片布局
- 🖱️ 交互式：滚动动画、点击展开、一键复制联系方式
- ⚡ 纯静态，加载快，无依赖
- 📄 同时提供 Word 文档版下载
