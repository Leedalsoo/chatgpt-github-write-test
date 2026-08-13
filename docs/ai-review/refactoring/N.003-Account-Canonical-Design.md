# N.003 — Account Canonical Design

- EXP: EXP-001
- Repository: Leedalsoo/KOSPI200_Bot
- Branch: Autobot_GPT
- Source: Notion AI 작업 관리

## Review Result

mock_ws_server.py가 PaperTradingAccount을 직접 import하고 세션 초기화에서 생성하는 실제 Runtime 경로를 확인. AccountEngine은 별도 회계 엔진으로 cash, realized PnL, fee, slippage, margin, unrealized PnL을 관리. 두 모델이 다른 상태 모델을 가지므로 단순 삭제/치환을 금지하고 단계적 래퍼화/대체 및 Golden Baseline 비교를 권고.
