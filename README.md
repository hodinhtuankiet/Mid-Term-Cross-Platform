# 🚀 Hướng Dẫn Chạy Capacitor Trên Android

## 📌 1. Cài Đặt Môi Trường
Trước khi chạy ứng dụng trên Android, cần đảm bảo đã cài đặt:
- [Node.js](https://nodejs.org/) (>=14)
- [Visual Studio Code](https://code.visualstudio.com/)
- [Android Studio](https://developer.android.com/studio) (cài đặt kèm Android SDK)
- Capacitor CLI:  
  ```
  npm install -g @capacitor/cli
  ``` 
## 📌 2. Tạo Hoặc Mở Dự Án
``` 
npx create-capacitor-app myApp
cd myApp
npm install
``` 
## 📌 3. Cài Đặt Capacitor
``` 
npm install @capacitor/core @capacitor/android
npx cap init
``` 
## 📌 4. Thêm Nền Tảng Android
npx cap add android
## 📌 5. Build & Chạy Trên Android
``` 
npm run build
npx cap sync android
npx cap open android
``` 
## 📌 6. Chạy Trực Tiếp Trên Thiết Bị Hoặc Giả Lập
``` 
npx cap run android
```
## 📌 Giao diện ứng dụng
![Image](https://github.com/user-attachments/assets/ce214a23-545a-4813-a337-750d060da6ec)




  
