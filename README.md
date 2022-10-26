# 주식 가격 예측

## 데이터
JPX 도쿄 증권 거래소 데이터
https://www.kaggle.com/competitions/jpx-tokyo-stock-exchange-prediction
데이터 수 : 2,332,531 개
Feature 수 : 12개

## 요약
주어진 데이터를 이용하여 생성한 보조지표 8개를 추가하여 LGBM으로 예측

## 결과
RMSE : 0.020594
![image](https://user-images.githubusercontent.com/27802354/197935489-eab09c4e-f8ab-4ec1-becc-4e91e2e90682.png)
![image](https://user-images.githubusercontent.com/27802354/197935505-c34f3740-342b-40ac-8124-a93cdbb2a97b.png)  
그다지 성능은 좋지 못했다. 

녹색 : 베이스모델
주황 : 예측
파랑 : 

## 그외
Feature importance 확인 결과 LGBM 모델에서는 캔들봉보다 보조지표가 더 중요했다.
![image](https://user-images.githubusercontent.com/27802354/197688261-bba4f2b4-6040-4a10-8f97-de72a07dcc81.png)
