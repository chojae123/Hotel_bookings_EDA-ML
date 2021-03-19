# Hotel_bookings_EDA-ML
###### 패스트 캠퍼스 프로젝트2 
###### 호텔 투숙객 예약정보 EDA / ML model 활용한 호텔 투숙객 취소여부 예측

### project개요
도심 호텔과 관광지호텔의 호텔 투숙객 예약정보가 담긴 kaggle data(hotel bookig demand)를 활용   
각 호텔의 고객의 예약정보를 통해 호텔 별 투숙객의 성향을 분석하고, 머신러닝 모델을 통해 호텔별 투숙객의 예약 취소 여부를 예측 

<image src = https://github.com/chojae123/Hotel_bookings_EDA-ML/blob/main/data/img/img1.png>
<image src = https://github.com/chojae123/Hotel_bookings_EDA-ML/blob/main/data/img/img2.png>  

### 실행
```
jupyternotebook 실행
전처리1(최종).ipynb 실행
전처리2_머신러닝전(최종).ipynb 실행
EDA notebook파일 3개 실행하여 시각화 정보 확인
머신러닝 notebook파일을 실행하여 취소 여부 예측에 대한 각 모델 별 성능 확인
```

### 사용데이터
[kaggle dataset - Hotel booking demand](https://www.kaggle.com/jessemostipak/hotel-booking-demand)

### 사용 라이브러리
- pandas
- matplotlib, seaborn
- skcikit learn(logistic regression, support vector machine, randomforest)
- xgboost
- catboost
- lightgbm

### 참여자
- [류정욱](https://github.com/jamey0320)
- [김다슬](https://github.com/Daseul-Kim)

### Citation

The data is originally from the article Hotel Booking Demand Datasets, written by Nuno Antonio, Ana Almeida, and Luis Nunes for Data in Brief, Volume 22, February 2019.

The data was downloaded and cleaned by Thomas Mock and Antoine Bichat for #TidyTuesday during the week of February 11th, 2020.
