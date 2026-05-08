# 南京微路文化传媒有限公司 官网

这是南京微路文化传媒有限公司的官方网站，用于GitHub组织验证。

## 网站特点

- ✅ 完整的公司介绍页面
- ✅ 详细的业务范围展示
- ✅ 团队介绍和案例展示
- ✅ 联系方式和留言表单
- ✅ 响应式设计，支持移动端和桌面端
- ✅ 现代化的UI设计和动画效果
- ✅ 丰富的内容，满足GitHub组织验证要求

## 技术栈

- HTML5
- CSS3 (Grid, Flexbox, 动画)
- JavaScript (原生，无框架依赖)
- Font Awesome 图标库
- Google Fonts (Noto Sans SC)

## 部署到 GitHub Pages

### 方法一：使用个人/组织仓库

1. 在GitHub上创建一个新的仓库，仓库名为 `你的用户名.github.io`（如果是组织账号则为 `组织名.github.io`）

2. 将本目录下的所有文件上传到仓库中

3. 进入仓库的 Settings -> Pages

4. 在 Source 中选择 `main` 分支，点击 Save

5. 稍等几分钟，网站就会部署到 `https://你的用户名.github.io`

### 方法二：使用项目仓库

1. 在GitHub上创建一个新的仓库（比如命名为 `weilu-website`）

2. 将本目录下的所有文件上传到仓库中

3. 进入仓库的 Settings -> Pages

4. 在 Source 中选择 `main` 分支，点击 Save

5. 网站会部署到 `https://你的用户名.github.io/weilu-website/`

**注意：** 由于使用了相对路径，直接打开本地的index.html可能无法正常加载CSS和JS。建议使用本地服务器预览，或直接部署到GitHub Pages后访问。

## 本地预览

如果需要在本地预览，可以使用以下方法：

### 使用 Python
```bash
# Python 3
python3 -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

然后在浏览器中访问 `http://localhost:8000`

### 使用 Node.js
```bash
npx serve
```

## 文件结构

```
weilu-website/
├── index.html          # 主页面
├── css/
│   └── style.css       # 样式文件
├── js/
│   └── script.js       # JavaScript脚本
└── README.md           # 说明文档
```

## 页面结构

1. **导航栏** - 固定顶部导航，支持移动端菜单
2. **Hero区域** - 公司标语和CTA按钮
3. **关于我们** - 公司介绍和统计数据
4. **核心价值观** - 公司的核心理念
5. **业务范围** - 6大服务项目介绍
6. **案例展示** - 4个代表性案例
7. **团队介绍** - 核心团队成员
8. **联系我们** - 联系方式和留言表单
9. **页脚** - 公司信息和快速链接

## 自定义修改

### 修改公司信息
- 编辑 `index.html` 中的相关内容
- 公司名称、地址、电话、邮箱等都可以直接修改

### 修改颜色主题
- 编辑 `css/style.css` 中的 `:root` 变量
- `--primary-color` - 主色调
- `--secondary-color` - 辅助色

### 添加真实图片
- 目前使用Font Awesome图标作为占位
- 可以替换为真实的公司图片、团队照片、案例图片等

## GitHub组织验证注意事项

为了确保通过GitHub的组织验证，网站需要满足：

1. ✅ 可以公开访问
2. ✅ 工作正常，链接和功能可用
3. ✅ 域名与组织相关联
4. ✅ 包含足够的公司信息，不是"即将上线"或内容极少的页面

本网站已经包含了完整的公司信息，满足GitHub组织验证的要求。

---

© 2024 南京微路文化传媒有限公司 Nanjing Weilu Culture Media Co., Ltd.
