# ㅇㅇ의 리뷰 · Portfolio by Juns

**Juns** 개인 포트폴리오용 정적 웹 프로젝트입니다.  
SNS 체험단 · 라이프스타일 리뷰 플랫폼 콘셉트(**ㅇㅇ의 리뷰**)의 랜딩 + 서버·인프라 기술 문서를 담았습니다.

> **데모 / 샘플 프로젝트** — 실제 운영 서비스가 아닙니다.  
> 도메인·이메일·전화 등 연락처는 모두 **example / 123** 형태의 가짜 값입니다.

## Live demo

| 구분 | 링크 |
|------|------|
| **GitHub Pages** | https://savvy773.github.io/happycomms/ |
| 서비스 소개 | https://savvy773.github.io/happycomms/service.html |
| 서버 · 인프라 기술 문서 | https://savvy773.github.io/happycomms/docs/server-infrastructure-plan.html |
| GitHub 저장소 | https://github.com/savvy773/happycomms |

## Sample contacts (placeholders)

| 항목 | 샘플 값 |
|------|---------|
| Domain | `www.example.com` |
| Email | `contact@example.com` |
| Phone | `010-1234-5678` |

실제 개인·회사 연락처는 포함하지 않습니다.

## Structure

```
happycomms/
├── index.html          # Entry hub (Service / Tech docs)
├── service.html        # Brand · service landing (concept)
├── docs/
│   └── server-infrastructure-plan.html
└── README.md
```

| Path | Description |
|------|-------------|
| `index.html` | Choose service intro or infrastructure plan |
| `service.html` | Experience-review platform concept landing |
| `docs/server-infrastructure-plan.html` | Plan A/B, HW specs, cost, security |

## Service concept (`service.html`)

- Tagline: *ㅇㅇ의 시선으로 좋은 경험을 리뷰합니다*
- Categories: food, travel, stay, **hospital/clinic**, beauty, home, café, fashion, kids, fitness, pets, etc.
- Campaign · creator matching · content ops (concept copy)

## Tech plan (`docs/…`)

Infrastructure proposal for a **small startup** CRM / intranet (portfolio case study).

| Topic | Content |
|-------|---------|
| Plan A | Managed cloud (Seoul) — monthly OPEX |
| Plan B | Office mini-server + offsite backup — CAPEX + low OPEX |
| HW | Instance / mini-PC BOM, UPS |
| Cost | Monthly breakdown, initial quote, 1–3y TCO |
| Security | Encryption, RBAC, audit, 3-2-1 backup |

Not a formal quote or legal advice.

## Local

Static HTML only — open in a browser or:

```bash
npx serve .
```

## GitHub Pages

- Branch: `main` · folder: `/` (root)
- URL: https://savvy773.github.io/happycomms/

## Author

- **Juns** — personal portfolio
- Brand mark in UI: **행복**
- Colors: lavender / deep purple (`#6B3FA0` family)

## License

© 2026 Juns. Portfolio demo. Sample data only.
