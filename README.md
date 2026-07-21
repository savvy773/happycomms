# Juns의 리뷰

[![GitHub Pages](https://img.shields.io/badge/demo-GitHub%20Pages-6B3FA0?style=flat-square)](https://savvy773.github.io/happycomms/)
[![HTML](https://img.shields.io/badge/stack-Static%20HTML-informational?style=flat-square)](#)
[![License](https://img.shields.io/badge/license-Portfolio%20demo-lightgrey?style=flat-square)](#license)

**Juns** 개인 포트폴리오용 정적 웹 사이트입니다.  
SNS 체험단 · 라이프스타일 리뷰 플랫폼 콘셉트 랜딩과, 소규모 스타트업 인프라 제안 문서를 포함합니다.

> **데모 전용** — 실제 운영 서비스가 아닙니다.  
> 연락처·도메인은 모두 `example` / `123` 형태의 **플레이스홀더**입니다.

---

## Demo

| Page | URL |
|------|-----|
| 홈 · 서비스 소개 | https://savvy773.github.io/happycomms/ |
| 서버 · 인프라 기술 문서 | https://savvy773.github.io/happycomms/docs/server-infrastructure-plan.html |
| 저장소 | https://github.com/savvy773/happycomms |

페이지 상단 메뉴로 홈 ↔ 기술 문서를 오갈 수 있습니다.

---

## Features

### 서비스 랜딩 (`index.html`)

- 태그라인: *Juns의 시선으로 좋은 경험을 리뷰합니다*
- 카테고리: 맛집, 여행, 숙소, **병원/클리닉**, 뷰티, 홈, 카페, 패션, 키즈, 피트니스, 펫 등
- 캠페인 · 크리에이터 매칭 · 콘텐츠 운영 콘셉트 카피
- 반응형 레이아웃 (Pretendard, 라벤더/딥퍼플 톤)

### 인프라 플랜 (`docs/server-infrastructure-plan.html`)

소규모 CRM / 인트라넷을 가정한 **포트폴리오 케이스 스터디**입니다. 견적·법률 자문이 아닙니다.

| Topic | Content |
|-------|---------|
| Plan A | 관리형 클라우드 (서울) — 월 OPEX |
| Plan B | 사무실 미니서버 + 오프사이트 백업 — CAPEX + 저 OPEX |
| HW | 인스턴스 / 미니 PC BOM, UPS |
| Cost | 월 비용 분해, 초기 견적 개념, 1–3년 TCO |
| Security | 암호화, RBAC, 감사, 3-2-1 백업 |

---

## Repository structure

```text
happycomms/
├── index.html                              # Main — service landing
├── docs/
│   └── server-infrastructure-plan.html     # Infra plan (linked from top nav)
└── README.md
```

| Path | Role |
|------|------|
| `index.html` | 메인 진입점 · 서비스 소개 |
| `docs/server-infrastructure-plan.html` | Plan A/B · HW · 비용 · 보안 |

**Navigation**

```text
index.html  ──[기술문서]──►  docs/server-infrastructure-plan.html
     ▲                              │
     └──────────[← 홈]──────────────┘
```

---

## Local development

빌드 도구 없이 정적 HTML만 사용합니다.

```bash
# clone
git clone https://github.com/savvy773/happycomms.git
cd happycomms

# option A — open directly
# open index.html in a browser

# option B — local static server
npx --yes serve .
```

브라우저에서 `http://localhost:3000` (serve 기본 포트)으로 확인하세요.

---

## GitHub Pages

| Setting | Value |
|---------|--------|
| Source | Deploy from branch |
| Branch | `main` |
| Folder | `/` (root) |
| Site URL | https://savvy773.github.io/happycomms/ |

`main`에 푸시하면 Pages가 루트 정적 파일을 게시합니다.  
별도 CI/CD 빌드는 없습니다.

---

## Sample contacts (placeholders)

| Item | Value |
|------|--------|
| Domain | `www.example.com` |
| Email | `contact@example.com` |
| Phone | `010-1234-5678` |

실제 개인·회사 연락처는 포함하지 않습니다.

---

## Author

- **Juns** — personal portfolio
- Brand mark: **행복**
- Palette: lavender / deep purple (`#6B3FA0`)

---

## License

© 2026 Juns. Portfolio demo only. Sample data. Not for commercial use as a live product brand.
