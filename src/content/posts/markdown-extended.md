---
title: Markdown 扩展功能
published: 2023-05-01
description: '了解有关 Markdown 功能的更多信息'
image: ''
tags: [Markdown]
category: 'Examples'
draft: false 
---

## GitHub 存储库卡片

您可以添加链接到 GitHub 存储库的动态卡片，在页面加载时，存储库信息将从 GitHub API 中提取。

::github{repo="vconlln/vconll.github.io"}

使用代码创建 GitHub 存储库卡 `::github{repo="<owner>/<repo>"}`.

```markdown
::github{repo="vconlln/vconll.github.io"}
```

## 警告

支持以下类型的警告: `note` `tip` `important` `warning` `caution`

:::note
突出显示用户应该考虑的信息，即使用户浏览时也应考虑。
:::

:::tip
帮助用户取得更大成功的可选信息。
:::

:::important
用户成功所必需的关键信息。
:::

:::warning
由于存在潜在风险，关键内容需要用户立即关注。
:::

:::caution
某一行为可能产生的负面后果。
:::

```markdown
:::note
Highlights information that users should take into account, even when skimming.
:::

:::tip
Optional information to help a user be more successful.
:::
```

警告的标题可以自定义。

:::note[我的自定义标题]
这是一条带有自定义标题的注释。
:::

```markdown
:::note[我的自定义标题]
这是一条带有自定义标题的注释。
:::
```

> [!TIP]
> [GitHub 语法](https://github.com/orgs/community/discussions/16925)也受支持。

```
> [!NOTE]
> GitHub 语法也受支持。

> [!TIP]
> GitHub 语法也受支持。
```

