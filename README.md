# DL2024_Team6_Stock-Prediction

本專案為中正大學資工所深度學習概論課程 - 第六組期末專題

專案利用股票技術分析方法，將資料標記為(買入/賣出/持有)三個類別，並將資料給LSTM加上1DCNN模型訓練，使用 2020~2022 年的股票資料作為訓練集，訓練一個能夠提供買入/賣出/持有建議的模型，並且將2023年的資料用作測試集，以驗證和評估我們訓練的模型，幫助投資者制定更明智的交易策略。

## 專案結構

1. 程式主檔：stock_prediction.ipynb
2. 所需套件.txt：requirement.txt
3. data資料夾：存放各股票2020~2023之資料
4. model_202122.h5、model_all.h5：已訓練好之模型檔案

## 使用方法

1. clone 專案
git clone https://github.com/yochen103/DL2024_Team6_Stock-Prediction.git

2. 安裝所需套件
pip install -r requirements.txt

3. 執行stock_prediction.ipynb檔中各cell，其中training部分如不想再跑一次請跳過勿執行，直接執行load model部分並接續後續cell(ipynb檔中有說明)