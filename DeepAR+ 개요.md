# 개념
0. Amazon ForecastDeepAR+는 RNN(반복 신경망)을 사용해 스칼라(1차원) 시계열을 예상하는 지도 학습 알고리즘

# 특징
0. 

# 기타
0. Target TS에는 결측값이 포함될 수 있다.(그래프에는 Blank로 표시됨)
1. DeepAR+는 미래에 대한 Feature TS를 활용한다. 이로 인해, 'What-if' 시나리오를 수행할 수 있다. 예를 들어, '제품의 가격을 변경하면 어떻게 될까?' 라는 시나리오를 기반으로 예측을 수행할 수 있다. 
2. Target TS는 많은 Categorical features(범주형 피처)들을 활용할 수 있음
