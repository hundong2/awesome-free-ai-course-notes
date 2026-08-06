# 02. 핵심 개념 교차 학습

## 하나의 공통 틀

대부분의 지도학습은 `가설 공간 + 손실 함수 + 최적화 + 평가`로 정리할 수 있습니다.

- 가설 공간: 어떤 함수를 후보로 허용할 것인가
- 손실 함수: 개별 예측의 오류를 어떻게 수치화할 것인가
- 최적화: 경험적 위험을 어떤 계산 절차로 줄일 것인가
- 평가: 보지 않은 data에서 일반화되는지 어떻게 판단할 것인가

## 과정별 강점

- MIT: 문제 정의부터 신경망·표현학습·순차 의사결정까지 연결
- LMU: risk minimization, resampling, tuning과 실제 data science lifecycle
- Caltech: finite sample에서 일반화가 가능한 조건과 VC dimension
- Cornell: 전통 ML algorithm의 직관과 구현 흐름
- Stanford: 지도·비지도·강화학습의 표준 수학 노트
- Harvard: 확률적 생성 모델, graphical model, HMM과 MDP

## 실습 질문

같은 binary classification data에 logistic regression, decision tree, k-NN을 적용하고 다음을 비교합니다.

1. 각 모델의 가설 공간은 무엇인가?
2. 학습 손실과 평가 metric은 같은가?
3. hyperparameter가 복잡도에 어떤 영향을 주는가?
4. class imbalance에서 accuracy가 왜 오해를 부를 수 있는가?
5. data leakage를 막기 위해 preprocessing을 어느 시점에 fit해야 하는가?
