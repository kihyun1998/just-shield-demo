# just-shield-demo

[just-shield](https://github.com/kihyun1998/just-shield)의 살아있는 데모 저장소.

`.github/workflows/supply-chain.yml`이 PR마다 just-shield를 돌려 결과를 SARIF로 GitHub 코드 스캐닝에 업로드한다 — 위반이 있으면 **PR의 해당 코드 줄 위에 경고 주석**이 달리고 검사 잡이 실패한다.

데모 PR에서 실제 동작을 볼 수 있다: 일부러 취약하게 만든 워크플로(가변 참조 `@master`, `permissions` 미선언, `curl | sh`)를 추가하는 PR에 just-shield가 어떻게 반응하는지.

모든 액션 참조는 커밋 SHA로 핀 고정되어 있다 — just-shield의 R1 규칙을 이 저장소도 지킨다.
