# Simple Blog

一個簡單的靜態部落格，使用純 HTML 和 CSS 構建。

## 專案結構

```
simple-blog/
├── index.html                              # 首頁
├── assets/                                 # 放全站通用的資源
│   └── style.css                           # 網站樣式
└── posts/                                  # 文章目錄
    ├── index.html                          # 文章列表頁面
    └── 2026-01-01-first-post/
        ├── index.html                      # 文章頁面
        └── img.webp                        # 文章圖片
```

## 如何使用

1. 直接在瀏覽器中開啟 `index.html` 即可瀏覽
2. 無需任何伺服器或建置工具
3. 可部署至任何靜態網站託管服務


## 如何新增文章

請參考文章：[如何新增一篇文章](posts/2026-01-03-how-to-create-a-post/index.html)

簡要步驟：

1. **複製一份資料夾**：選擇 `posts/` 中的任一文章資料夾並複製
2. **修改資料夾名稱**：重新命名為 `YYYY-MM-DD-文章標題` 格式
3. **修改文章內容**：編輯 `index.html` 中的標題、日期和內容
4. **更新文章列表**：在 `posts/index.html` 中加入新文章的連結
