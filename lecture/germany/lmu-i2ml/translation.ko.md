# LMU I2ML 머신러닝 입문 - 한국어 번역 해설

원문: [Introduction to Machine Learning](https://slds-lmu.github.io/i2ml/) · [Chapters](https://slds-lmu.github.io/i2ml/chapters/)

확인일: 2026-08-06

## 과정 소개

video, PDF slide, cheat sheet, quiz, solution이 있는 exercise와 notebook을 제공하는 self-study 과정입니다. 1-10장은 학부 입문, 11-19장은 석사 수준의 이론, 20-26장은 실제 ML project의 함정과 best practice를 다룹니다.

## 장 제목 번역

### 기초: 1-10장

1. ML 기초
2. 지도 회귀
3. 지도 분류
4. 성능 평가
5. k-nearest neighbors
6. classification and regression tree
7. random forest
8. neural network
9. hyperparameter tuning
10. nested resampling

### 이론 심화: 11-19장

11. 고급 risk minimization
12. multiclass classification
13. information theory
14. 차원의 저주
15. regularization
16. linear SVM
17. nonlinear SVM
18. boosting
19. Gaussian process

### 응용 심화: 20-26장

20. data science lifecycle
21. feature selection
22. preprocessing와 data leakage
23. probability calibration
24. imbalanced learning
25. model ensemble과 stacking
26. OpenML과 대규모 benchmarking

추가 장으로 multitarget learning과 online learning이 있으며 Python/scikit-learn 및 R/mlr3 coding 자료도 제공합니다.

## 이 과정의 핵심 관점

새 algorithm 이름을 외우기보다 `hypothesis space, risk, optimization`이라는 공통 구성 요소로 supervised learning을 설명합니다. risk minimization, 통계적 parameter estimation, Bayesian 관점과 information theory를 서로 전환해 보는 것이 주요 목표입니다.

## 권장 사용법

처음 학습하면 1-10장의 video·quiz·exercise를 순서대로 수행하세요. 실무자는 20-26장을 먼저 훑고 필요한 이론 장으로 역참조할 수 있습니다. resampling 안에서 preprocessing과 tuning을 수행해 leakage를 막는지 특히 확인해야 합니다.

> 원 사이트는 자료 source와 각 파일의 이용 조건을 별도로 제공할 수 있습니다. 본 문서는 chapter 설명을 한국어로 번역·요약한 학습 안내이며 원본 slide나 exercise를 재배포하지 않습니다.
