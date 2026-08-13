# N.002 — Account 실제 Runtime 호출경로 및 정본 소유권 조사

- EXP: EXP-001
- Repository: Leedalsoo/KOSPI200_Bot
- Branch: Autobot_GPT
- Source: Notion AI 작업 관리

## Review Result

AccountEngine과 core/contracts.py의 실제 존재를 확인하고, 이후 Runtime에서 Account 상태를 생성·변경·조회하는 객체를 추적하기로 함. PaperTradingAccount 명칭과 실제 구현을 재검증하고 정본 소유권 근거를 수집하며 코드 수정 전 변경 범위를 결정하도록 함.
