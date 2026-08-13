# N.005 — Account Mapping Plan 추가 정합성 검토

- EXP: EXP-001
- Repository: Leedalsoo/KOSPI200_Bot
- Branch: Autobot_GPT
- Source: Notion AI 작업 관리

## Review Result

AccountEngine과 PaperTradingAccount 외에도 hft/core/state.py의 AccountState, hft/core/execution_agent.py의 직접 Account 상태 변경, hft/main_server.py의 SessionContext.account 사용을 발견. Account 모델이 최소 3개로 분산되어 있으므로 기존 범위를 재조정하고 금융/Runtime 변경 구현을 보류.
