# N.010 — Account Dual-Read Implementation

- EXP: EXP-001
- Repository: Leedalsoo/KOSPI200_Bot
- Branch: Autobot_GPT
- Source: Notion AI 작업 관리

## Review Result

AccountEngine, core/contracts.py, PaperTradingAccount 실제 구현을 확인하고 두 모델의 total_equity 의미가 다름을 확인. Runtime 파일을 수정하지 않고 tests/unit/test_account_dual_read_exp001.py 하나로 characterization test를 추가하는 비파괴적 검증안을 제안. 실제 파일 생성은 실행 AI/CLI가 수행하도록 전달.
