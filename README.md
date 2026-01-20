# 闭气+ - GitHub Pages

这个仓库用于托管闭气+（Apnea Trainer）应用的静态页面。

## 🌐 访问地址

网站地址：https://xueshaoy.github.io/apneatrainer-pages/

## 📄 页面列表

- [主页](./index.html) - 应用导航页面
- [隐私政策](./apneatrainer-privacy-policy.html) - 闭气+应用的隐私政策页面

## 🚀 部署方式

本项目使用 **GitHub Actions** 自动部署到 GitHub Pages：

- 工作流文件：`.github/workflows/static.yml`
- 触发条件：推送到 `main` 分支时自动部署
- 部署状态：可在仓库的 [Actions](https://github.com/xueshaoy/apneatrainer-pages/actions) 标签页查看

## 📁 项目结构

```
apneatrainer-pages/
├── index.html                          # 主页导航页面
├── apneatrainer-privacy-policy.html    # 隐私政策页面
├── README.md                           # 项目说明文档
└── .github/
    └── workflows/
        └── static.yml                  # GitHub Actions 部署工作流
```

## 🔄 更新说明

1. 直接提交更改到 `main` 分支
2. GitHub Actions 会自动触发部署流程
3. 部署完成后，更改会在几分钟内生效

## 📝 文件说明

- `index.html` - 应用主页，提供导航链接
- `apneatrainer-privacy-policy.html` - 应用的隐私政策页面
