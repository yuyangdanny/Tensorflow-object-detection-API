# Tensorflow 2D object detection API


Process:
# 1.Make your own data:
<br>step1.Take pictures on your object.
<br>step2.Divide your data into train and test.
<br>step3.Label your datasets:you can use labelImg to label they, the tutorial can find in my present repositories on github[LabelImg](https://github.com/yuyangdanny/labeling-tool "labelImg")
# 2、Normalize datasets:
<br>step1.After yot use the label tool (labelImg) you can get the file that filename Extension with .xml and concert it to .csv.
<br>step2.Convert .csv file into .TFRecord file.
# 3.Train:
step1.whit trainsfer learing you can get a nice accuracy! and you can find the model at model zoo in open source on here [github上的模型庫](https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/detection_model_zoo.md "模型庫")
<br>if you want the detection speed you can choose SSD or mobilenet.
<br>if you want the detection speed you can choose Xception.
