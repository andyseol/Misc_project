Miscellaneous Projects 기타 프로젝트  

1. Task1  
- 목표: 물질의 물성 데이터에 관한 자유 분석  
- 데이터: 1689물질(sample), 2031물성(feature)  
- 접근: 회귀문제. Train 1000샘플 / Test 689샘플  
- 결과: RandomForest를 이용. R2=0.995, RSME=0.124  

2. Task2  
- 목표: 목표물성을 최대화하는 분자 탐색  
- 데이터1: 1000분자(sample), 2978물성(feature) (中 2개가 목표물성) ...train_dataset  
- 데이터2: 8538분자(sample), 2976물성(feature) ...population  
- 데이터1을 이용하여 데이터2에서 탐색  
- 접근: 회귀문제. 데이터1에서 Train 800샘플 / Test 200샘플  
- 결과: RandomForest를 이용. R2=0.754, RSME=0.528  
- 예측치 상위 20샘플을 선정  
