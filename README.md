# 구내식당 식수인원 예측
2023학년도 1학기 경제분석을 위한 데이터사이언스 과제입니다.
https://dacon.io/competitions/official/235743/overview/description

test set은 코로나가 심했던 기간이며, 구내식당 이용 인원은 코로나와 유의한 관계가 있을 것인데
train set의 상당수 기간은 코로나가 나오기 전이거나 코로나가 경남 진주까지 유행하지는 않았던 시기가 많았음.

train set을 오버샘플링하고 LGBM 모델을 적용해서 문제를 해결함

https://dacon.io/competitions/official/235743/leaderboard
(메커니즘 디자이너) 31/810등으로 MAE 기준 약 상위 4%
