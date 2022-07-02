# Список с выполненными проектами:
## 1. Классический ML <br>
Прогнозирование оттока клиентов <br>
https://github.com/GermanYanchenko/ClassicML
<br>
Исходный датасет<br>
![alt text](https://github.com/GermanYanchenko/projects/blob/main/example/ML_classic.png?raw=true)
![alt text](https://github.com/GermanYanchenko/projects/blob/main/example/ML_classic1.png?raw=true)
<br>
В качестве базовых алгоритмов исследованы kNN, LogisticRegression, DesisionTreeClassifier, GradientBoostingClassifier, RandomForestClassifier и SupportVectorClassification.Также реализован stacking, в качестве мета-алгоритма используется XGBoost.<br>
Метрика качества - кривая AUC-ROC, полученные значения: <br><br>
![alt text](https://github.com/GermanYanchenko/projects/blob/main/example/metric.png?raw=true)<br>
![alt text](https://github.com/GermanYanchenko/projects/blob/main/example/metric1.png?raw=true)
<br>
## 2. Computer Vision <br>
### 2.1 Бинарный классификатор <br>
https://github.com/GermanYanchenko/ImageClass_binary <br>
![alt text](https://github.com/GermanYanchenko/projects/blob/main/example/IC_history.png?raw=true)<br>
![alt text](https://github.com/GermanYanchenko/projects/blob/main/example/IC_predict.png?raw=true)<br>
### 2.2 Transfer Learning and Fine Tuning <br>
Для задачи 2.1 в качестве базовой модели выбрана MobileNet, заморозив модель и дополнив выходным полным слоем реализовано обучение, после разморозив слои было выполнено дообучение.<br>
https://github.com/GermanYanchenko/TransferLearn_FineTun<br>
Значения потерь и качества при Transfer Learning: <br>
![alt text](https://github.com/GermanYanchenko/projects/blob/main/example/hist_trans_learn.png?raw=true)<br>
Значения потерь и качества при Fine Tuning: <br>
![alt text](https://github.com/GermanYanchenko/projects/blob/main/example/hist_fine_tun.png?raw=true)<br>
Предсказание модели: <br>
![alt text](https://github.com/GermanYanchenko/projects/blob/main/example/predict_tl_ft.png?raw=true)<br>
### 2.3 Модель предсказания пола, расы и вовзраста лиц людей.
txt
Img
### 2.4 Детектирование человеческого лица при работе с webcam
https://github.com/GermanYanchenko/CV_facedetection_webcam
![alt text](https://github.com/GermanYanchenko/projects/blob/main/example/facedetection.gif?raw=true)
