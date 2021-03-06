# 運用Python進行AI的深度學習

## 一、AI與深度學習的基本概念
- 人工智慧核心概念為深度學習，而深度學習的核心技術為神經網路
- 三種重要的模型：NN、CNN、RNN
- AI的創建過程
  - (1)問一個問題
  - (2)化成函數形式(數學建模)
  - (3)準備訓練資料
  - (4)架構神經網路(如NN、CNN、RNN、強化學習與GAN)，調整參數並獲得函數
  - (5)檢驗訓練結果，使用loss function
- 標準神經網路(Fully Connected Neural Networks)基本概念
- 神經網路訓練法backpropagation：
  使用既有資料進行訓練並修正
- 梯度下降法(gradient descent)：
  控制其他參數(為常數)，並只調整一個變數，形成只有一個變數的函數

## 二、實作NN神經網路
- 範例：使用mnist資料建立手寫辨識機器

## 三、卷積神經網路(CNN)概念與實作
- CNN特色：用不同"filter"，以區塊辨識不同特徵。
- 範例：使用mnist資料建立手寫辨識機器

## 四、遞歸神經網路(RNN)概念與實作
- RNN特色一：會記憶先前輸出結果，並回傳當成新的輸入。
- RNN特色二：輸入值與輸出值可以為不同的類型的資料，如輸入圖片並輸出文字。
- 範例：使用imdb資料建立正負評價的情意分析

## 五、其他神經網路的建構技術與應用
- 靈活建立轉移學習模型
- 範例：將原0~9數值輸出的CNN參數，轉移到0、1輸出值學習模型。

## 六、不同功能的神經網路
- 合併(merge)結構：輸入來自多層的神經網路層的合併結果。
- 分歧(branch)結構：單層神經網路輸出至不同層的神經網路。
- 具平均/抽樣的神經網路層

## 七、自編碼模型(Autoencoder)
- AE模型概念與實作
- VAE模型概念與實作
