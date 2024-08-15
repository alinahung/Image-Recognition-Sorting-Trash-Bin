# 專案名稱

## 軟體

1. **MIT App Inventor**（開發手機 APP）
2. **Personal Image Classifier (PIC) Tools**（影像辨識訓練）
3. **MAKE CODE**（編寫 micro:bit 的程式控制伺服馬達）

## 硬體

1. **Android 手機** * 1
2. **BBC micro:bit 微控制板** - 新版 V2.21 * 1
3. **[DFRobot] micro:bit 電機驅動擴充板** * 1
4. **伺服馬達 SG90 TOWER PRO 1.8KG 扭力** * 3

## 執行流程

1. **藍芽連線micro:bit**：透過藍芽連線至micro:bit
2. **影像辨識垃圾**：透過手機拍照辨識回收物。
3. **垃圾桶開與關**：透過藍牙傳送指令到 micro:bit，藉由 micro:bit 控制對應的垃圾桶（伺服馬達）開啟與關閉。
4. **分類的結果統計**：將垃圾分類的結果紀錄在試算表中。
<img width="469" alt="截圖 2024-08-15 晚上11 25 02" src="https://github.com/user-attachments/assets/523d54d5-6f56-4e85-8bc0-e12e5cab1ce5">

## 遇到的問題與解決方式

- **問題**：資源回收物（如紙餐盒）打開、關閉、方向不同可能導致辨識準確度降低，垃圾桶無法順利開闔。
- **解決方式**：增加訓練資料的多樣性與數量，調整伺服馬達的角度與開關停滯時間。

## 成果影片


https://github.com/user-attachments/assets/f3a3bfd7-5578-4305-9a51-b5d6e541b8ec

