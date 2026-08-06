# 03. 고급 학습과 검증

## 고급 경로

1. Caltech에서 generalization bound와 VC dimension을 학습합니다.
2. Berkeley에서 확률·최적화 기반 derivation과 modern deep learning을 확장합니다.
3. Princeton에서 supervised·unsupervised·learning theory를 한 체계로 정리합니다.
4. Oxford에서 Bayesian modeling, probabilistic programming, Monte Carlo, MCMC와 variational inference를 학습합니다.

## 재현 체크리스트

- random seed, package version, hardware와 data version 기록
- train/validation/test 분할 단위를 명시하고 leakage 검사
- 단순 baseline과 동일 metric으로 비교
- 평균뿐 아니라 variance 또는 confidence interval 보고
- hyperparameter 탐색에 test set을 사용하지 않기
- 실패한 실험과 제외 기준도 보존

## 보안과 윤리

공개 강의의 예제 data라도 개인정보, 차별 가능성, license와 용도 제한을 확인합니다. 모델 성능은 배포 안전성을 보장하지 않으며, distribution shift·adversarial input·monitoring과 rollback 계획을 별도로 검토해야 합니다.

## 기여 전 링크 감사

원문 URL의 HTTP 상태만 확인하지 말고 제목, 교수자, 학기, 자료 유형과 로그인 필요 여부도 확인합니다. redirect가 다른 강의로 연결되거나 최신 학기에서 서술형 노트가 사라진 경우 이를 기록하고 원본 색인을 갱신합니다.
