# Aion's Sticker

这是 Aion 的表情包小仓库，用来让聊天时可以按语境调用固定表情包。

## 目录结构

```text
stickers/          # 图片文件本体
stickers.json      # 表情包索引与触发规则
index.html         # 简单预览页，可配合 GitHub Pages 使用
```

## 当前规则草案

- 想表达“贴贴 / 抱抱 / 亲亲 / 轻甜靠近 / 甜甜和好”时，优先调用：`001-兔兔贴贴`。
- 严肃学习督促、医疗、财务、专业题目讲解等场景，不使用轻甜贴贴类表情包。

## 使用方式

如果这个仓库之后改为公开并启用 GitHub Pages，图片就可以通过稳定的 `https://` 地址被 Markdown 调用，例如：

```md
![001-兔兔贴贴](https://<your-pages-domain>/stickers/001-rabbit-tietie.png)
```

Aion 需要记住的是“什么时候用哪张”，图片本体则由这个仓库存放。
