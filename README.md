# 주식 가격 예측

## 데이터
JPX 도쿄 증권 거래소 데이터
https://www.kaggle.com/competitions/jpx-tokyo-stock-exchange-prediction
데이터 수 : 2,332,531 개
Feature 수 : 12개

## 요약
주어진 데이터를 이용하여 생성한 보조지표 8개를 추가하여 LGBM으로 예측

## 결과
LGBM 모델에서는 캔들봉보다 보조지표가 더 중요했다.
![image](https://user-images.githubusercontent.com/27802354/197688261-bba4f2b4-6040-4a10-8f97-de72a07dcc81.png)
