
# **政大磨課師_成為python數據分析達人的第一課_課程筆記**

## 1.Python程式基礎I：Python的開發環境、串列與繪圖
### 1.1 Jupyter魔術指令pylab
  1. inline表示於網頁中顯示結果(較不建議使用)
  `%pylab inline' inline`
  2. 其餘指令：`pi`、`sin()`、`plot()`、`randn()`取亂數
### 1.2 markdown筆記
  1. 如何設定標題次序
  2. 加入超連結、插入圖片、數學符號
### 1.3 List
  1. Python如何定義List
  2. List的運算
### 1.4 Hello World
  1. 字串定義與運用
  2. 換列符號：三引號
  3. `print()`
### 1.5 拍拍機器人(互動式程式語言)
  1. `input()`
  2. 美金換算與拍拍機器人範例
  
## 2.Python程式基礎II：迴圈、條件判斷
### 2.1 條件判斷
  數值大小與條件設定，如`and`、`or`
### 2.2 while迴圈
### 2.3 字串格式化 `.flot()`
  ```
  message= "嗨，來自{}的{}".format(place, name)
  print(message)
  ```
### 2.4 函數撰寫
### 2.5 函數練習
  `
  def say_hi(name, place):
      message= "嗨，來自{}的{}！".format(place, name)
      return message
  `
### 2.6 List切割(空隙次序)
### 2.7 字串切割(空隙次序)
### 2.8 List快速生成
  `L = list(range(10, 18))`
  `list("ABCDEFG")`
### 2.9 for迴圈
### 2.10 搜索資料 `in`
### 2.11 if條件判斷
  `message = input(">> ")
  if ("Y" in message):
      print("OK")
  elif ("N" in message):
      print("OK")
  else:
      print("NO！")`
### 2.12取整數亂數`randint()`

## 3.Python強大的秘密：numpy、向量化與各式套件
### 3.1 正規讀套件方式
  `%matplotlib inline 
  import numpy as np 
  import matplotlib.pyplot as plt
  import pandas as pd`
### 3.2 處理List資料 `.append()`
### 3.3 Array(盡量以array取代迴圈，節省計算速度) `np.array()` `np.dot()`
### 3.4 Array資料結構轉換 
  1. `array.shape()=`直接改變資料結構
  2. `array.reshape()` 並不取代既有資料結構
### 3.5 Array資料快速生成
  1. `array(XY=[[X,Y] for X in range(10) for y in range(5)])`
  2. `np.zeros([x,y])`、`np.ones([x,y])`
  3. `np.eye(n)`單位矩陣
### 3.6 Array畫圖
  1.`plt.plot(y)`
  2.`np.linspace()`等距取點
### 3.7 Array篩選資料 array = array[條件]
  `
  plt.plot(x, y)
  plt.plot(x[y>0], y[y>0], "o")
  `

## 4.處理與展示資料的技巧：Python的字典檔與jupyter互動功能
### 4.1


## 5.試算表：pandas數據分析

## 6.預測未來：用線性迴歸做預測

## 7.成為機器學習專家：機器學習概要
