# Tensorflow 2D物體檢測 API

流程分為:
# 一、自製數據集:
step1.拍攝圖像
<br>step2.圖像標記並將數據集分為訓練集與測試集
<br>圖像標記可以由labelImg標記，相關教學可以到我之前發布的github上查詢[LabelImg](https://github.com/yuyangdanny/labeling-tool "labelImg")
# 二、整理數據集:
step1.將labelImg工作完之後的.xml檔轉換為csv檔
<br>step2.將csv檔轉換為可供訓練用的TFRecord檔
# 三、訓練模型:
step1.使用遷移學習來訓練此模型，遷移模型可在開源模型庫找到[github上的模型庫](https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/detection_model_zoo.md "模型庫")
<br>　　　＊如果追求速度可以使用ssd_mobilenet
<br>　　　＊追求精準度可以使用xception
<br>(該模型還在調參數優化訓練中..)
# 四、demo real-time檢測效果:
<br>希望未來可以實現real-time的檢測效果。
