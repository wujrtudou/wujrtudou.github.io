# GitHub 个人主页专业化配置建议

## 1. 创建 Profile README 仓库

仓库名必须与你的 GitHub 用户名完全一致，并设置为 **Public**。把本文件包中的 `README.md` 放在仓库根目录。

建议仓库结构：

```text
<your-github-username>/
├── README.md
└── Jinran_Wu_CV.pdf
```

CV 建议统一使用稳定文件名 `Jinran_Wu_CV.pdf`，避免文件名中出现版本号或括号。

## 2. GitHub 账户资料建议

- **Name**: `Jinran Wu`
- **Bio**: `Research Fellow @ UQ | Statistical learning, semi-supervised inference, robust forecasting & computational statistics`
- **Company**: `The University of Queensland`
- **Location**: `Brisbane, Australia`
- **Website**: 填写确认可访问的个人主页地址
- **Social links**: 优先放 Google Scholar、ORCID 和 LinkedIn

## 3. 建议置顶的 6 个仓库

置顶仓库不应全部是零散实验代码，建议形成清晰的研究组合：

1. 半监督学习与 informative missingness 的方法仓库
2. 自动超参数选择的支持向量回归仓库
3. 异方差或稳健支持向量回归仓库
4. 电力负荷概率预测仓库
5. 环境或海洋预测的 physics-informed learning 仓库
6. 一个高质量教程、综述代码或可复现实验模板仓库

每个置顶仓库应至少包含：

- 一句话说明研究问题和贡献
- 论文引用与 DOI
- 环境安装方法
- 最小可运行示例
- 数据来源与许可说明
- 复现实验命令
- `CITATION.cff`
- 开源许可证

## 4. 仓库命名方式

使用简洁、可搜索、能体现方法与任务的英文名称，例如：

```text
informative-missingness-ssl
adaptive-svr
heteroscedastic-svr
probabilistic-load-forecasting
physics-informed-sediment-forecasting
statistical-learning-reproducibility-template
```

避免使用：`test1`、`new-code`、`final-version`、`paper-code-v2-final` 等名称。

## 5. 每个研究仓库的 README 结构

```markdown
# Project Title

One-sentence contribution statement.

## Overview
## Method
## Installation
## Quick Start
## Reproducing the Paper
## Data
## Results
## Citation
## Licence
## Contact
```

README 开头应优先回答三个问题：做什么、为什么重要、如何运行。不要先堆放公式、日志或完整论文摘要。

## 6. 视觉与内容原则

- 主页保持学术、克制、国际化，主语言使用英文。
- 不建议使用大量 GitHub trophies、访问量动画、贪吃蛇贡献图或过多技术徽章。
- 不要把所有论文都堆到主页；主页只保留 4–6 篇代表作，其余链接到 Google Scholar。
- 技术栈只列真实、持续使用并能从仓库体现的工具。
- 头像、姓名、单位、ORCID、Google Scholar 中的英文姓名应保持一致。

## 7. 发布前检查

- 所有链接均可打开
- 邮箱和 ORCID 正确
- 当前职位与单位正确
- 代表论文年份、期刊、作者顺序正确
- 删除无内容或重复仓库
- 为置顶仓库添加 Topics，例如 `statistical-learning`、`semi-supervised-learning`、`forecasting`、`robust-statistics`、`support-vector-regression`
- 默认分支统一为 `main`
- 开启 GitHub Discussions 仅用于确实需要交流的项目
