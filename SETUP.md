# GitHub 主页优化 — 手动步骤（仅需一次）

## 1. 启用 Profile README（主页置顶介绍）

1. 打开 https://github.com/new  
2. 仓库名必须填：**`bukeke111`**（与用户名完全一致）  
3. 选 **Public**，勾选 **Add a README**  
4. 创建后，用本目录的 `README.md` 内容替换仓库内 README  
5. 或本地执行：

```bash
cd github-profile
git init
git add README.md
git commit -m "Add profile README"
git branch -M main
git remote add origin https://github.com/bukeke111/bukeke111.git
git push -u origin main
```

## 2. 完善个人资料（Settings → Profile）

访问：https://github.com/settings/profile

建议填写：

| 字段 | 建议内容 |
|------|----------|
| **Name** | Claire |
| **Bio** | 教育科技 · 高校学术治理 · ARGP 产品原型 · AI × 流程 |
| **URL** | https://github.com/bukeke111/AI-academic-review |
| **Location** | （选填，如 China） |

## 3. 固定精选仓库（Pinned repositories）

访问：https://github.com/bukeke111?tab=repositories  
点击 **Customize your pins**，固定：

1. **AI-academic-review**（旗舰项目）  
2. **vibebar1.0** 或 **desktop**（展示技术广度）

## 4. 为 AI-academic-review 添加 Description & Topics

仓库 → **Settings** → 或在仓库主页右侧 **About** 编辑：

- **Description**：`高校学术项目评审与治理平台交互 Demo（ARGP）· AI 质检 / 答辩预演 / 公示异议`
- **Topics**：`education` `academic` `demo` `governance` `javascript` `ai` `product-prototype`
