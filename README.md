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

## 功能
1. **回收物拍照與辨識功能**：
   使用手機拍照並通過影像辨識技術來辨識不同種類的回收物。

2. **藍牙數據傳輸與指令發送功能**：
   透過手機的藍牙功能，將辨識結果傳送至 micro:bit。
   
4. **垃圾桶控制功能**：
   micro:bit 接收到手機傳來的指令後，根據不同的回收物類別，控制相應的伺服馬達開啟和關閉垃圾桶。

5. **分類結果記錄與統計功能**：
   將回收物分類的結果記錄在試算表中，便於後續統計與分析。
   
## 執行流程

1. **藍芽連線micro:bit**：透過藍芽連線至micro:bit
2. **影像辨識垃圾**：透過手機拍照辨識回收物。
3. **垃圾桶開與關**：透過藍牙傳送指令到 micro:bit，藉由 micro:bit 控制對應的垃圾桶（伺服馬達）開啟與關閉。
4. **分類的結果統計**：將垃圾分類的結果紀錄在試算表中。
<!-- <img width="700" alt="截圖 2024-08-15 晚上11 25 02" src="https://github.com/user-attachments/assets/523d54d5-6f56-4e85-8bc0-e12e5cab1ce5"> -->
<img width="467" alt="截圖 2024-08-23 下午6 08 40" src="https://github.com/user-attachments/assets/2bf27e88-e47e-49b9-9a16-1fe7233bf73c">

## 遇到的問題與解決方式

- **問題**：資源回收物（如紙餐盒）打開、關閉、方向不同可能導致辨識準確度降低，垃圾桶無法順利開闔。
- **解決方式**：增加訓練資料的多樣性與數量，調整伺服馬達的角度與開關停滯時間。

## 成果影片


https://github.com/user-attachments/assets/f3a3bfd7-5578-4305-9a51-b5d6e541b8ec

