# Voice

Kaggle에서 발견한 음성 데이터 자료 "Gender Recognition by Voice"를 기반으로 머신러닝 및 딥러닝 모델을 만들어 목소리 판별 학습.


## 개발환경

Python 3.9 - Jupyternotebook

## 테스트 데이터 - 학습한 모델이 잘 돌아가는지 확인하기 위해 음성데이터 수집
카운터테너 목소리 데이터  
일반 남자 고음 목소리 데이터  
일반 남자 저음 목소리 데이터  
배우 김혜수님 목소리 데이터  
일반 여자 목소리 데이터  
짱구 목소리 데이터  

## 결론
머신러닝 모델인 DecisionTreeClassifier의 결과값은 [1, 0, 1, 0, 0, 0]이므로 정확도는 83.3%이지만 일반 남자의 고음 목소리 데이터를 판별을 하지는 못했음. 
딥러닝 모델 결과값은 [0 ,0 ,1, 0, 0, 0]으로 정확도는 66%로 일반 남자 저음 목소리 데이터만 구별을 했음. 
즉, 딥러닝이 머신러닝보다 더 발전됐다 믿었으나 예상외에 결과를 보였다. 
데이터가 적을 때는 머신러닝이 효율적인 모습을 보였다. 


