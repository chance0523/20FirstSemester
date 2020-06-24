### 기본코딩

- pandas
- txt to csv

### 데이터분석

- regresssion

  - 실측값과의 차이(입실론)를 구해서 least square
  - logistic regression
    - 비연속성 범주형 데이터에 사용. (bool 데이터 같은)

- 연관성분석
  - 지지도, support
    - P(X)
  - 신뢰도, confidenct
    - X를 산 사람이 Y도 살 확률
    - P(Y|X)
  - 향상도, lift
    - P(XandY) / P(X)\*P(Y)
    - A,B의 시청이 랜덤한 경우에 비해 A와의 관계가 고려되어 시청되는 비율 (1에서 멀수록 더 상관이 있음)
    - 1이면 독립. 서로 상관이 없다.
- 의사결정나무

- KNN

- SVM

  - 마진 : 집단을 분류하는 분류선을 그렸을 때 가장 두꺼운 분류선의 넓이
  - 절댓값 안에 있는 값들이 양수라고 가정. cos세타 값이 양수 (세타가 90도보다 작음)

- 워드클라우드

- 클러스터링

  - RFM
    - Recency : 최근성
    - Frequency : 구매빈도
    - Monetary : 구매금액
  - K-means

    - 각 군집에 속하는 데이터와의 거리를 최소화하는 중심점
    - 중심점을 평균, 거리 계산, 나눠야 할 군집의 수가 k

  - DBSCAN
  - 단위 맞추는게 중요

- 신경망분석
