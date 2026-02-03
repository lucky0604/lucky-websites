# Lucky Websites

统一管理所有 Lucky 开发的 App 网站。

## 目录结构

```
lucky-websites/
├── docly/                   # Docly App 网站
│   ├── index.html
│   ├── privacy.html
│   └── terms.html
├── app2/                    # App2 网站（待开发）
│   ├── index.html
│   ├── privacy.html
│   └── terms.html
└── shared/                  # 共享模板和资源
    ├── templates/
    └── assets/
```

## 部署方式

每个 App 使用独立的子域名和 Vercel 项目：

- **Docly:** https://docly.fastdata.top
- **App2:** https://app2.fastdata.top

## 添加新 App

1. 创建 App 目录：`mkdir -p app3`
2. 复制模板或创建网站文件
3. 提交到 Git
4. 在 Vercel 创建新项目（Root Directory: `./app3`）
5. 添加子域名（如 `app3.fastdata.top`）

## 技术栈

- **托管:** Vercel
- **域名:** fastdata.top
- **版本控制:** Git + GitHub
