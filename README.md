# multivariate-regression

카메라에서 받아온 센싱값들로부터 다변수회귀를 수행한다.   
c++ 프로젝트에 포팅이 원활하게 이루어져야 하므로 어떠한 수식 형태의 모델을 필요로 한다. 

## Feature engineering
* 방향을 가지는 numerical feature를 one-hot encoding 을 이용해서 방향 feature 생성.
* 위에서 생성된 새 feature에 대해 기존 feature 포함 전체 scaling 수행. -> scaling이 종속변수에 미치는 영향?

