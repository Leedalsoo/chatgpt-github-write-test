# N.007 — Account Canonical Migration Design

- EXP: EXP-001
- Repository: Leedalsoo/KOSPI200_Bot
- Branch: Autobot_GPT
- Source: Notion AI 작업 관리

## Review Result

AccountEngine을 canonical accounting engine으로 사용할 경우 필요한 상태·계산 확장, PaperTradingAccount/AccountState 대응표, cash/realized PnL/fee/slippage/margin/unrealized PnL 및 futures/options valuation/settlement의 authoritative owner를 확정해야 함. 실제 Runtime Account 소유권 변경은 HARD APPROVAL 대상.
