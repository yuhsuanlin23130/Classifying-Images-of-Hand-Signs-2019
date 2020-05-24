#### 說明
以DenseNet作為網路模型架構，訓練手勢圖像的數字的分類與預測，前處理包含圖片蒐集、Image Augmentation、資料集生成。test accuracy約為85%。
 
#### 執行環境
Python3 + Jupyter Notebook      
mxnet

#### 目錄結構說明
* training7: 3878 training images (included image augmentation)
* testing: 300 testing images
* preprocess.ipynb: Resize原始圖片, Image Augmentation
* train.ipynb: 資料集生成, DenseNet模型建構與訓練, 模型測試
* net.params: 最終模型參數
