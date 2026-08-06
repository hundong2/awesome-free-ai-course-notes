# MIT 6.390 머신러닝 입문 - 한국어 번역 해설

원문: [6.390 IntroML Notes](https://introml.mit.edu/notes/)

확인일: 2026-08-06

## 과정 소개

이 과정은 data를 이용해 예측하거나 의사결정하는 원리를 최적화 관점에서 설명합니다. 모델을 고르는 일만이 아니라 문제 정의, data 수집, 가정, 평가 방식, 영향을 받는 사람과 배포 결과까지 ML 시스템 설계의 일부로 봅니다.

## 원문 흐름의 한국어 정리

1. **도입**: 지도·비지도·순차·강화학습을 구분하고, 문제 class·가정·평가 기준·model class·algorithm을 정의합니다.
2. **선형 모델**: 회귀와 분류를 선형 hypothesis와 loss minimization 문제로 표현합니다.
3. **최적화와 일반화**: gradient 기반 학습, regularization, train/test 성능 차이를 다룹니다.
4. **비선형 모델**: feature transformation, kernel과 model capacity를 학습합니다.
5. **신경망**: feed-forward network, activation, backpropagation, batch 학습, dropout과 normalization을 설명합니다.
6. **표현학습**: self-supervised·contrastive·multimodal learning, autoencoder와 embedding을 연결합니다.
7. **순차 모델과 의사결정**: state machine, sequence model, MDP와 reinforcement learning의 기본 구조를 다룹니다.

## 핵심 개념

- **가설(hypothesis)**: 입력에서 출력을 계산하는 후보 함수입니다.
- **손실(loss)**: 하나의 예측이 실제 값과 얼마나 다른지 나타냅니다.
- **위험(risk)**: 가능한 data 분포에서 기대하는 평균 손실입니다.
- **귀납 가정**: 과거 sample로 미래를 예측하려면 train과 query가 관련 있다는 가정이 필요합니다.

## 권장 학습법

각 장에서 `입력과 출력 → 가정 → hypothesis class → objective → optimization → evaluation` 여섯 항목을 표로 다시 작성하세요. 신경망 장은 선형 모델과 gradient descent를 먼저 이해한 뒤 읽는 편이 좋습니다.

> 이 문서는 원문의 구조를 따른 번역 해설입니다. 수식·그림·연습문제의 정확한 표현은 CC BY-NC-SA 4.0 원문을 확인하세요.
