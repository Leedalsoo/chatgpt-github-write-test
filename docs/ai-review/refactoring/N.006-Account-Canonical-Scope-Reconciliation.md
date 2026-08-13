# N.006 — Account Canonical Scope Reconciliation

- EXP: EXP-001
- Repository: Leedalsoo/KOSPI200_Bot
- Branch: Autobot_GPT
- Source: Notion AI 작업 관리

## Review Result

AccountEngine, PaperTradingAccount, AccountState의 세 상태 모델과 mock_ws_server.py/hft/main_server.py의 두 Runtime 경로를 비교. AccountEngine을 canonical accounting engine 후보로 두되 기존 Runtime 의미를 보존하고 Golden Baseline을 먼저 고정한 후 단계적으로 배선하기로 판정.
