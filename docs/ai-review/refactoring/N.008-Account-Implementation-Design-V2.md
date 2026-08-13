# N.008 — Account Implementation Design V2

- EXP: EXP-001
- Repository: Leedalsoo/KOSPI200_Bot
- Branch: Autobot_GPT
- Source: Notion AI 작업 관리

## Review Result

세 Account 모델과 두 Runtime 경로의 구조를 재확인. Adapter/Facade, Runtime 직접 치환, 단계적 Dual-Read 세 가지 배선안을 비교하고 C 방식 Dual-Read 검증 후 A 방식 단계적 배선을 권고. PaperTradingAccount과 AccountState를 즉시 삭제하지 않고 금융 계산 의미가 다른 영역은 별도 판정.
