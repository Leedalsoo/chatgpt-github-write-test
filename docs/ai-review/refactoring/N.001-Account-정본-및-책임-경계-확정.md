# N.001 — Account 정본 및 책임 경계 확정

- EXP: EXP-001
- Repository: Leedalsoo/KOSPI200_Bot
- Branch: Autobot_GPT
- Source: Notion AI 작업 관리

## Review Result

Notion AI 작업 관리의 첫 Account 검토 결과. account/account_engine.py의 AccountEngine, core/contracts.py의 AccountSnapshot/순수 계산, mock_ws_server.py의 PaperTradingAccount 사용 경로를 비교하도록 결정. Account 모듈을 새로 만들지 않고 기존 책임과 실제 호출 경로를 1:1 비교하며, 금융/Runtime 구조 변경은 승인 전 실행하지 않기로 판정.
