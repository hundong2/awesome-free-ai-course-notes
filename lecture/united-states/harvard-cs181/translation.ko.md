# Harvard CS181 머신러닝 - 한국어 번역 해설

원문: [CS181 Textbook repository](https://github.com/harvard-ml-courses/cs181-textbook)

확인일: 2026-08-06

## 과정 소개

Harvard 학부 머신러닝 과정용 textbook입니다. repository는 LaTeX source와 완성 PDF를 제공하며, 오류는 장·page를 명시해 issue로 보고하도록 안내합니다.

## 장 구성 번역

- **ML Introduction**: 학습 문제, notation과 평가의 기본 틀
- **Linear Regression**: 확률적 관점과 최소제곱 기반 회귀
- **Classification**: binary·multiclass 예측과 decision boundary
- **Support Vector Machines**: margin maximization과 kernel
- **Neural Networks**: 다층 표현과 backpropagation
- **Clustering**: label 없이 sample 구조를 찾는 방법
- **Mixture Models**: 여러 잠재 분포가 data를 생성한다는 모델
- **Generative Models**: joint distribution을 통해 관측값을 설명하는 접근
- **Graphical Models**: 조건부 독립성을 graph로 표현
- **Hidden Markov Models**: 관측되지 않는 상태를 가진 sequence model
- **Dimensionality Reduction**: 중요한 축을 보존하며 차원을 줄이는 방법
- **Markov Decision Processes**: 상태·행동·보상·전이로 순차 의사결정 표현
- **Reinforcement Learning**: interaction으로 policy 또는 value를 학습

## 학습 관점

이 자료의 강점은 discriminative model만이 아니라 확률적 생성 모델, graphical model과 순차 의사결정을 한 교재에서 연결한다는 점입니다. 회귀·분류 다음 mixture model과 graphical model을 읽고, HMM에서 시간 구조를 익힌 뒤 MDP·RL로 넘어가면 자연스럽습니다.

## source를 직접 빌드할 때

원 저장소 안내에 따라 LaTeX가 설치된 환경에서 `master/` 디렉터리의 `master.tex`를 `pdflatex`로 compile합니다. 생성 PDF는 기여 commit에 포함하지 않는 것이 원 프로젝트 규칙입니다.

> 본 문서는 장 제목과 학습 목적을 번역·해설한 자료입니다. 교재 본문과 수식은 원 저장소의 license 및 기여 지침을 확인한 뒤 이용하세요.
