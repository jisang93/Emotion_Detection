# Emotion_Detection

#### Face Detection을 이용한 표정의 감정 탐지



#### 활용 패키지

> `Selenium`, `Face Detection`, `pickle`



#### 활용 데이터 Set(Data Crawling)

> 1. 네이버 이미지
> 2. 구글 이미지



#### 데이터 전처리(Data Preprocessing)

> 1. 정확한 감정을 측정하기 위해 표정을 탐지해주는 Face Detection 이용
>    * 관련 출처 : https://github.com/davisking/dlib-models
> 2.  `pickle` 형태로 저장



#### 딥러닝을 이용한 모델링

> 1. CNN 모델
>    * Test Accuracy : 15.72
> 2.  VGGNet 모델
>    * 13층 Test Accuracy : 23.46
>    * 16층 Test Accuracy : 52.39
> 3. ResNet 모델(40층)
>    * Test Accuracy : 80.87



#### 실제 탐지 결과

![그림1](README.assets/그림1.png)