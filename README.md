# Happycomms · 언니의기록

SNS 체험단 · 라이프스타일 리뷰 플랫폼 **언니의기록** 공개 페이지입니다.  
서비스 소개와 서버·인프라 기술 문서를 **선택 허브**에서 분기해 볼 수 있습니다.

## 배포 URL

| 구분 | 링크 |
|------|------|
| **GitHub Pages (메인)** | https://savvy773.github.io/happycomms/ |
| 서비스 소개 | https://savvy773.github.io/happycomms/service.html |
| 서버 · 인프라 기술 문서 | https://savvy773.github.io/happycomms/docs/server-infrastructure-plan.html |
| GitHub 저장소 | https://github.com/savvy773/happycomms |
| 공식 사이트 | https://www.unnigirok.com |

## 페이지 구성

```
happycomms/
├── index.html          # 진입 허브 (서비스 / 기술문서 선택)
├── service.html        # 브랜드 · 서비스 소개 랜딩
├── docs/
│   └── server-infrastructure-plan.html   # Plan A/B · HW · 비용 · 보안
└── README.md
```

| 경로 | 설명 |
|------|------|
| `index.html` | 2개 경로 선택 화면 — 서비스 소개 또는 기술 문서 |
| `service.html` | 체험단·카테고리·프로세스·협업 문의 랜딩 |
| `docs/server-infrastructure-plan.html` | 소규모 스타트업 서버·인트라넷 기술 플랜 |

## 서비스 소개 (`service.html`)

- 브랜드 메시지: *언니의 시선으로 좋은 경험을 기록합니다*
- 주요 카테고리: 맛집, 여행·숙박, **병원·클리닉**, 뷰티, 가전·생활, 리빙, 카페·디저트, 패션, 육아·키즈, 헬스, 반려동물 등
- 캠페인 · 크리에이터 매칭 · 콘텐츠 관리 안내

## 기술 문서 (`docs/…`)

소규모 팀 기준 **고객·인플루언서·매출·사내 인트라넷** 데이터 운영을 위한 인프라 제안입니다.

| 섹션 | 내용 |
|------|------|
| Plan A | 관리형 클라우드 (AWS 서울 / NCP 등) — 월 OPEX 중심 |
| Plan B | 사무실 미니서버 + 오프사이트 백업 — 초기 CAPEX + 낮은 월비 |
| HW 스펙 | 클라우드 인스턴스 · 미니 PC BOM · UPS 등 |
| 비용 | 항목별 월 비용, 초기 견적, 1~3년 TCO 비교 |
| 보안 | 암호화, RBAC, 감사 로그, 백업 3-2-1 등 |

> 기술 문서는 **기술 제안용**이며 견적·법률 자문이 아닙니다.

## 로컬에서 보기

별도 빌드 없이 정적 HTML입니다.

```bash
# 저장소 클론 후
start index.html          # Windows
# 또는 브라우저에서 파일 직접 열기
```

로컬 서버를 쓸 경우 예:

```bash
npx serve .
# → http://localhost:3000
```

## GitHub Pages

- **Branch**: `main`
- **Folder**: `/` (root)
- 배포 주소: https://savvy773.github.io/happycomms/

`main`에 푸시하면 Pages가 자동 갱신됩니다 (보통 1~2분).

## 브랜딩 메모

- 로고 마크: **행복**
- 컬러: 라벤더 · 딥 퍼플 (`#6B3FA0` 계열) 파스텔 배경
- 폰트: Pretendard Variable (CDN)

## 라이선스 · 문의

- © 언니의기록 / Happycomms  
- 공식: [www.unnigirok.com](https://www.unnigirok.com)
