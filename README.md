# 论文图码对照

这是一个 GitHub Agent Skill，名称是 **论文图码对照**（`paper-figure-code`）。

仓库：[tongruizhang1097-crypto/paper-figure-code](https://github.com/tongruizhang1097-crypto/paper-figure-code)

## 做什么

粘贴论文的 DOI 或 arXiv 编号，或提供本地论文 / 代码。技能会查找公开实现（优先官方或教学实现），再生成可交互的「左代码 / 右模块图」双向对照，并用中文向初学者讲解各个模块。

## 安装

需要支持 `gh skill` 的 [GitHub CLI](https://cli.github.com/)：

```bash
gh skill install tongruizhang1097-crypto/paper-figure-code
```

## 使用

安装之后，在支持 Agent Skills 的代理对话里直接调用即可。粘贴 DOI、arXiv 编号，或附上本地论文 / 代码，并说明要做论文图码对照，例如：

> 用论文图码对照看这篇：arXiv:1706.03762

代理会按技能说明查找公开实现，并交付左侧代码、右侧模块图的交互对照。

## 许可

[MIT License](LICENSE)。Copyright (c) 2026 TERRY_Z。
