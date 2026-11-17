# baitaoshu.github.io

白桃书的项目主页 —— https://baitaoshu.github.io

一站纸白底的静态单页：介绍白桃书是什么、有哪些功能、公版书库在哪、怎么取用。
没有框架、没有构建、没有依赖，就一个 `index.html`。

## 关于白桃书

**https://baitaoshu.com** — 免费的中文小说阅读站。

- 793 本在架小说，25 部古典名著的公版全文
- 故事地图：把书里可考的地名落到地图上，标出首次出现的章回与原文
- 浏览器听书、段落点评、全文检索
- 简体 / 繁體 / 日本語 / English 四种界面

## 相关仓库

| 仓库 | 内容 |
|---|---|
| [books](https://github.com/baitaoshu/books) | 25 部古典名著公版全文，Markdown + `index.json`，CC0 |
| [baitaoshu](https://github.com/baitaoshu/baitaoshu) | 账号主页 |

## 本地预览

```bash
python3 -m http.server 8000
# 打开 http://localhost:8000
```

## 授权

页面代码 MIT，文字内容 CC BY 4.0，书籍正文属公有领域（详见 [books 仓库的 LICENSE](https://github.com/baitaoshu/books/blob/main/LICENSE)）。
