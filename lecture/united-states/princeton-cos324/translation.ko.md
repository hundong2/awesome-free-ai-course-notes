# Princeton COS 324 머신러닝 입문 - 한국어 번역 해설

원문: [COS 324 Notes](https://princeton-introml.github.io/)

작성: Sanjeev Arora, Danqi Chen, Simon Park, Dennis Jacob

확인일: 2026-08-06

## 과정 소개

Princeton의 머신러닝 입문 강의 노트입니다. 전체 PDF와 개별 chapter를 제공하며, errata를 별도로 관리합니다. 단순 algorithm 목록보다 왜 학습이 가능한지와 model 간 관계를 수학적으로 설명하는 데 초점을 둡니다.

## 한국어 학습 지도

1. **지도학습**: linear regression에서 시작해 classification, optimization과 regularization으로 확장합니다.
2. **비선형 예측**: feature map, kernel, tree와 neural network가 표현력을 얻는 방식을 비교합니다.
3. **비지도학습**: clustering과 차원 축소로 label 없는 data의 구조를 찾습니다.
4. **확률적 모델**: likelihood, latent variable과 생성 관점을 이용해 불확실성을 표현합니다.
5. **학습 이론**: model complexity, sample 수와 generalization의 관계를 분석합니다.

## 읽을 때 확인할 질문

- objective function의 각 항은 어떤 가정을 반영하는가?
- optimization error와 generalization error를 구분했는가?
- 같은 data에서 discriminative와 generative 접근의 차이는 무엇인가?
- theorem의 결론을 적용하려면 어떤 독립성·분포 가정이 필요한가?

공식 사이트의 last updated와 실제 PDF version이 다를 수 있으므로 인용할 때 file의 version과 접근일을 함께 기록하세요.

> 이 문서는 과정의 구조와 핵심 질문을 한국어로 옮긴 해설입니다. 원문 전체를 재배포하지 않으며 정확한 정리·증명·그림은 공식 노트를 기준으로 합니다.
