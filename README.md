# Hwahii 課程 Landing Pages

這個儲存庫包含 Hwahii 的四個課程 landing pages，部署在 GitHub Pages 上。

## 🎯 課程連結

- **家庭 × 生產力系統**: https://hwahii.github.io/hwahii-courses/course-1-family/
- **生活自理重啟系統**: https://hwahii.github.io/hwahii-courses/course-2-reset/
- **知識系統 × 輸出引擎**: https://hwahii.github.io/hwahii-courses/course-3-knowledge/
- **中年轉型決策工作坊**: https://hwahii.github.io/hwahii-courses/course-6-transition/

## 📁 專案結構

```
hwahii-courses/
├── course-1-family/        # 家庭 × 生產力系統
├── course-2-reset/         # 生活自理重啟系統
├── course-3-knowledge/     # 知識系統 × 輸出引擎
├── course-6-transition/    # 中年轉型決策工作坊
└── shared/                 # 共用樣式
```

## 🚀 本地開發

1. Clone 此儲存庫：
```bash
git clone https://github.com/hwahii/hwahii-courses.git
cd hwahii-courses
```

2. 啟動本地伺服器：
```bash
python3 -m http.server 8000
```

3. 在瀏覽器中開啟：
- http://localhost:8000/course-1-family/
- http://localhost:8000/course-2-reset/
- http://localhost:8000/course-3-knowledge/
- http://localhost:8000/course-6-transition/

## 📝 更新內容

要更新 landing pages：

1. 編輯對應課程資料夾中的檔案
2. Commit 並 push 到 GitHub
3. GitHub Pages 會自動重新部署（通常需要 1-2 分鐘）

## 🎨 技術細節

- 純 HTML/CSS/JavaScript（無框架）
- 響應式設計，支援行動裝置
- 使用共用樣式系統確保一致性
- FAQ 手風琴互動功能
- 平滑捲動導航

## 📄 授權

© 2026 Hwahii. All rights reserved.
