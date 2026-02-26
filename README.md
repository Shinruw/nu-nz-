# 暖字表達寫作班 官方網站

> 先暖心，再暖字。

## 本地預覽

```bash
# 需要 Ruby >= 3.0（建議用 Homebrew 安裝）
export PATH="/usr/local/opt/ruby/bin:/usr/local/lib/ruby/gems/4.0.0/bin:$PATH"

bundle install
bundle exec jekyll serve
```

瀏覽器開啟 http://localhost:4000

## 新增教學札記

在 `_posts/blog/` 建立新檔案，命名格式：`YYYY-MM-DD-標題.md`

```yaml
---
layout: post
category: blog
title: "文章標題"
date: 2026-03-15
tags: [標籤一, 標籤二]
---

文章內容寫在這裡...
```

## 新增學生作品

在 `_posts/works/` 建立新檔案，命名格式：`YYYY-MM-DD-學生姓名-作品標題.md`

```yaml
---
layout: post
category: works
title: "作品標題"
author: 學生姓名
grade: 高年級
date: 2026-03-15
---

作品內容貼在這裡...
```

## 放置圖片

- 老師照片：`assets/images/teacher.jpg`
- 課堂照片：`assets/images/class-1.jpg`、`class-2.jpg`、`class-3.jpg`

## 更新 LINE 連結

在以下檔案將 `your-line-id` 替換為實際的 LINE ID：
- `_includes/line-float.html`
- `pages/contact.md`

## 部署到 GitHub Pages

1. 推送到 GitHub repository
2. 在 Settings → Pages 設定 `main` branch 為來源
3. 網站自動部署完成
