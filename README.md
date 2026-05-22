# Jungki Overview

박정운(Jungwoon Park)의 LLM Wiki 시스템 시각화. 2026-05-22 스냅샷.

## Live
- 🌐 https://jungki-overview.vercel.app

## 내용
- Jungki vault 5층 구조
- Karpathy 3-동작 사이클 (Ingest · Query · Lint)
- 슬래시 25개 모델 자동 분기 (Haiku/Sonnet/Opus)
- 21 specialized agents 자동 라우팅 + Escalation
- 글로벌 ↔ vault 동기화 인프라
- 멀티 머신 운영 정책

## 배포
GitHub push → Vercel 자동 deploy.

```bash
# 로컬 미리보기
open index.html

# Vercel 수동 deploy (선택)
vercel --prod
```

## 관련
- Vault 본체: `~/jungki/` (Private — GitHub `Jungwoon/jungki`)
- 정책 단일 소스: `~/jungki/setup/global-CLAUDE.md`
