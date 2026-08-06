# Oxford 머신러닝 고급 주제 - 한국어 번역 해설

원문: [Course page](https://www.cs.ox.ac.uk/teaching/courses/2019-2020/advml/) · [Bayesian Machine Learning PDF](https://www.cs.ox.ac.uk/files/11549/main.pdf)

교수자: Tom Rainforth

확인일: 2026-08-06

확인 범위: 과정 페이지와 118쪽 PDF의 표지·목차·확인 가능한 본문

## 과정 소개

deep learning, Bayesian ML과 NLP 응용을 다루는 고급 과정입니다. 이 폴더는 원본 README가 지목한 Tom Rainforth의 Bayesian ML 1-6강과 공식 course note를 중심으로 설명합니다.

## PDF 목차 번역

1. **도입**: 고급 절 표시와 읽는 방법
2. **확률의 간단한 소개**: random variable, event, conditioning, independence, density, expectation, measure와 variable transformation
3. **머신러닝 paradigm**: data로부터 학습, discriminative 대 generative ML, Bayesian paradigm, Bayesian과 frequentist 관점
4. **Bayesian modeling**: 기본 가정, Bernstein-von Mises theorem, graphical model, 예제 model, nonparametric Bayesian model과 Gaussian process
5. **Probabilistic programming**: simulator inversion, 접근법의 차이, Bayesian model을 program code로 표현하기
6. **Bayesian inference와 Monte Carlo 기초**: posterior 계산의 어려움, deterministic approximation, Monte Carlo와 기본 추론법
7. **고급 추론법**: 차원의 저주, MCMC와 variational inference

## 1-6강의 학습 흐름

ML paradigm → Bayesian modeling → graphical model·probabilistic programming → posterior·marginal likelihood·expectation → importance sampling과 Monte Carlo → MCMC·variational inference → variational autoencoder로 이어집니다.

## 선수 지식과 실습

probability, linear algebra, multivariate calculus와 Python 능력이 필요합니다. coin의 unknown bias처럼 작은 model에서 prior·likelihood·posterior를 손으로 계산한 뒤 importance sampling과 MCMC 결과를 analytic posterior와 비교하는 방식이 좋습니다.

## 번역·저작권 경계

PDF에는 `© Tom Rainforth 2020`이 표시됩니다. 따라서 이 문서는 제목·목차와 핵심 학습 흐름만 번역·해설하고, 본문 문장·수식·그림을 전문 복제하지 않습니다. 정확한 정의와 증명은 공식 PDF를 확인하세요.
