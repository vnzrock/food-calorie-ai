# Food Calorie AI

一個幫助使用者拍照估算食物卡路里的 App  
（利用 Open Source AI 模型 + 營養資料庫，快速做出 MVP）

---

## 🎯 MVP 功能
- 拍照上傳食物
- AI 辨識食物種類
- 預估熱量 (卡路里)
- 簡單飲食紀錄

---

## 🔗 Open Source 資源

### 食物影像辨識模型
- [foodai/food-recognition](https://github.com/ankit-ai/food-recognition)  
- [TensorFlow Food-101 Example](https://github.com/tensorflow/datasets/blob/master/docs/catalog/food101.md)  

### 營養成分資料庫
- [USDA FoodData Central API](https://fdc.nal.usda.gov/api-guide.html)  
- [台灣食物營養成分資料庫](https://consumer.fda.gov.tw/Food/TFND.aspx)  

### App 開發框架
- [Expo (React Native)](https://expo.dev/)  

---

## 🛠 技術規劃
- 前端 (App)：React Native + Expo
- 後端 API：Python + FastAPI
- AI：預訓練食物辨識模型 (PyTorch / TensorFlow)
- 資料庫：SQLite / Firebase  

---

## 📆 開發路線概覽

### Week 1：跑起 AI Demo
- Day 1：建立 GitHub repo + 收集 open source 資源（今天）
- Day 2：fork 食物辨識 repo → 測試圖片輸出結果
- Day 3：測試更多食物圖片，觀察辨識準確度
- Day 4：串接 USDA API → 食物名稱 → 卡路里
- Day 5：完成「圖片 → 食物 → 卡路里」程式
- Day 6-7：紀錄測試結果，學會修改程式

### Week 2：後端 API
- 包裝辨識流程成 FastAPI 後端
- 測試 POST 圖片 → 回傳 JSON

### Week 3：App Prototype
- 建 React Native + Expo App
- 拍照 → 上傳 → 顯示卡路里

### Week 4：MVP 完整功能
- UI 美化
- 飲食紀錄功能
- 小範圍 Beta 測試
