# 🚀 上線到 GitHub Pages — 步驟教學

## 第一步：下載並解壓縮網站檔案

把你拿到的 ZIP 解壓縮，確認資料夾結構長這樣：

```
running-site/
├── index.html        ← 首頁
├── courses.html      ← 課程頁
├── calculator.html   ← 配速計算機
├── contact.html      ← 聯絡我們
├── css/
│   └── style.css
└── js/
    └── main.js
```

---

## 第二步：建立 GitHub 帳號

1. 前往 [https://github.com](https://github.com)
2. 點右上角 **Sign up** 免費註冊

---

## 第三步：建立新的 Repository（倉庫）

1. 登入後點右上角 **＋** → **New repository**
2. Repository name 填：`running-site`（或你想要的名字）
3. 勾選 **Public**
4. 點 **Create repository**

---

## 第四步：上傳網站檔案

1. 在新建的 repository 頁面，點 **uploading an existing file**
2. 把 `running-site` 資料夾裡的 **所有檔案和資料夾** 拖進去
3. 確認所有檔案都上傳完成（包含 css/ 和 js/ 資料夾）
4. 下方 Commit changes 點 **Commit changes**

---

## 第五步：開啟 GitHub Pages

1. 進入 repository 頁面，點上方 **Settings**
2. 左側選單找 **Pages**
3. Source 選 **Deploy from a branch**
4. Branch 選 **main**，資料夾選 **/ (root)**
5. 點 **Save**

---

## 第六步：等待約 1–2 分鐘

頁面上會出現你的網址，格式長這樣：

```
https://你的帳號名稱.github.io/running-site/
```

🎉 完成！你的網站上線了！

---

## 日後更新網站內容

1. 在 GitHub 上找到要修改的檔案
2. 點鉛筆 icon ✏️ 直接線上編輯
3. 改好後點 **Commit changes**
4. 大約 1 分鐘後網站就更新了

---

## 常見問題

**Q: 網站打開是空白的？**
A: 確認 `index.html` 有直接放在 repository 根目錄，不是放在子資料夾裡。

**Q: CSS 沒有載入，網站樣式跑掉？**
A: 確認 `css/` 資料夾有正確上傳，路徑要和 `index.html` 裡的一致。

**Q: 想換成自己的網域名稱？**
A: 在 Pages 設定裡有 Custom domain 欄位，填入你的網域即可。

---

## 需要修改什麼？

| 想改什麼 | 去哪個檔案改 |
|---------|------------|
| 品牌名稱 | 所有 `.html` 檔案裡的 `YourBrand` |
| 聯絡電話/信箱 | `contact.html` |
| 課程內容 | `courses.html` |
| 首頁文字 | `index.html` |
| 顏色/字體 | `css/style.css` |
