# 🦀 Crabby’s Home

这是一个极简风格的个人导航主页模板，已配置为 GitHub + Cloudflare Pages 自动部署。

## 文件结构

```
index.html
style.css
icons/
  ├─ nas.svg
  ├─ download.svg
  ├─ photo.svg
  └─ link.svg
README.md
```

## 使用方法

### 1. 上传到 GitHub
1. 新建一个仓库，例如 `homepage`
2. 上传此文件夹内所有文件到仓库根目录
3. 提交（Commit changes）

### 2. 部署到 Cloudflare Pages
1. 登录 Cloudflare → Pages → Create a project
2. 连接 GitHub 仓库
3. Build settings:
   - Framework preset: None
   - Build command: 留空
   - Output directory: `/`
4. 点击 Deploy site
5. 可在 “Custom domains” 绑定自定义域名，例如 `home.crabby.me`

### 3. 更新主页
- 在 GitHub 网页端修改 `index.html` 或 `style.css` → Commit changes
- Cloudflare Pages 自动部署更新
