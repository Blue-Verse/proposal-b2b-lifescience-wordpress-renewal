# B2B 생명과학 홈페이지 리뉴얼 및 워드프레스 구축 — 제안 분석 로그

> 생성일: 2026-05-07
> 공고 URL: https://www.wishket.com/project/155137/

## 1. 공고 파싱 결과

```yaml
job:
  title: "B2B 생명과학 홈페이지 리뉴얼 및 워드프레스 구축"
  category: "웹 자사몰 구축, 퍼블리싱·반응형 / 워드프레스 리뉴얼"
  budget_range: "800~1,000만원 (상한 1,000만원)"
  duration: "90일 (3~4개월 이내 완료 희망)"
  start: "계약 체결 후 즉시 시작"
  client_team: "PM 1명, 디자이너 1명"
  priority: ["산출물 완성도", "금액", "일정 준수"]
  tech_stack:
    - WordPress
    - Astra
    - Elementor
    - Bootstrap
    - Salesforce MCAE
    - GA4
    - SSL/HTTPS
  description: >
    생명과학 연구 및 분석 장비를 중심으로 한 공식 홈페이지 전면 리뉴얼.
    응용분야 중심 IA로 잠재 고객(Lead) 확보 및 세일즈 전환율 향상을 목표로 함.
    글로벌 기술 기업 수준의 전문적이고 신뢰감 있는 브랜드 이미지 구축.
    모바일 최적화, IA, CMS 고도화, CRM(Salesforce MCAE) 연동을 통한 데이터 기반 운영 체계.
  requirements:
    - "메뉴 구성도 기반 기획 고도화 + UI/UX 디자인"
    - "워드프레스 기반 웹/관리자페이지/서버·DB·인프라"
    - "응용분야 스토리텔링형 UI (Challenge → Solution → Reference → Product)"
    - "제품 ↔ 응용분야 N:N 자동 연결"
    - "통합 검색 (제품명/제목/본문/첨부파일명, 브랜드·응용분야 필터)"
    - "Salesforce MCAE CRM 자동 연동, GA4 분석"
    - "SEO + GEO(Generative Engine Optimization) 최적화"
    - "팝업/프로모션 관리, 자료실(PDF/이미지/Video/웨비나 다시보기)"
    - "관리자 교육 + 운영 매뉴얼"
    - "PC / 태블릿 / 모바일 전면 반응형, SSL/HTTPS"
  client_questions:
    - "관리자 교육 및 운영 매뉴얼 제공 가능 여부"
    - "워드프레스 커스터마이징 테마 및 수준"
    - "B2B 기술 기업 홈페이지 구축 경험 / 유사 레퍼런스"
  deadline: "2026-05-21"
  job_post_url: "https://www.wishket.com/project/155137/"
  urls:
    - "https://www.cytivalifesciences.co.kr/"
    - "https://inside.lgensol.com/"
    - "https://service.chayon.co.kr/customer/reference-room"
  images: []
```

## 2. URL/이미지 분석

### Cytiva Korea (https://www.cytivalifesciences.co.kr/)
- **IA 패턴**: 응용분야(mAb, 바이러스 벡터, mRNA 등 연구 목적별) 카테고리 + 제품(크로마토그래피·세포배양·여과 등 기술 기반) 분류의 듀얼 분류 체계
- **자료실**: 기술별 집계, 워크샵·교육 프로그램 강조
- **UX**: 슬라이더 기반 홍보존(데모/신제품/이벤트), 다단계 드롭다운 네비게이션, 상단 고정 고객센터/카톡 1:1
- **신뢰성**: Heritage·Trustmark 로고, 산업 보고서(Global Biopharma Index)

### 자연과학 자료실 (https://service.chayon.co.kr/customer/reference-room)
- **자료 5종**: News(23) / Documents(43) / Webinar(32) / Video(3) / Others(2)
- **분류**: 브랜드별 분류 (Eurofins Discovery 69, Anabios 22 등)
- **뷰 모드**: gallery / magazine / list 3종
- **검색**: 인기 검색어(Kinase, Obesity, GLP1, Safety) + 정렬(시간순/조회순/알파벳)

### LG에너지솔루션 Battery Inside (https://inside.lgensol.com/)
- **카테고리**: News / Tech / Story / Opinion 4분류
- **태그 시스템**: 양극재·음극재·분리막·전해질 등 기술 용어 태그화
- **레이아웃**: 카드 형식(이미지+제목+설명) + 발행 날짜 + 다층 네비게이션
- **인게이지먼트**: Newsletter 구독, Battery Quiz(상호작용), Interview 섹션, 다국어(KOR/ENG)

### 제안서 반영
- **PRD 3.3 응용분야**: Cytiva의 응용분야 중심 IA + LG Battery Inside의 태그 시스템 적용
- **PRD 3.4 자료실**: 자연과학 자료실의 4종 분류(Document/News/Webinar/Video) + 브랜드·응용분야 필터 + 3뷰 모드 직접 차용
- **PRD 3.10 마케팅**: LG의 카드 레이아웃 + 발행 날짜 패턴 적용
- **차별화 포인트**: "참고 사이트 분석 결과" 섹션에 위 인사이트를 명시하여 분석 역량 어필

## 3. 실현 가능성 분석 (내부용)

### 프로젝트 유형
- 워드프레스 기반 FE 중심 웹 (CMS 커스터마이징, 어드민 패널) + 외부 API 연동(Salesforce MCAE)
- Feasibility: **가능** (조건부)
- 기간 버퍼: **+15%** (Salesforce 외부 API 보안 리뷰)

### 기본 공수 (AI 보조 없이)

| 작업 영역 | 기본 공수 (M/D) |
|-----------|----------------|
| 기획/설계 (메뉴 IA 고도화, 와이어프레임, 명세) | 8 |
| Figma 디자인 (메인+9개 섹션, 반응형 3종) | 14 |
| FE 개발 (테마 커스터마이징, 카드, 검색, Custom Block) | 20 |
| BE 개발 (CPT, N:N, 검색, Salesforce, 팝업, 자료실) | 14 |
| SEO/GEO + GA4 + 교육·매뉴얼 + QA/배포 | 12 |
| **합계** | **68** |

### AI 반영 공수

| 작업 영역 | AI 절감률 | 조정 공수 (M/D) |
|-----------|----------|----------------|
| 기획/설계 | 35% | 5.2 |
| Figma 디자인 | 15% | 11.9 |
| FE 개발 | 65% | 7.0 |
| BE 개발 | 55% | 6.3 |
| 운영/QA | 55% | 5.4 |
| **합계 (소계)** | | **35.8** |
| 버퍼 (+15%, 외부 API 연동) | | **41.2** |

### 클라이언트 예상 기간 vs 산정 기간
- 달력 일수: 41.2 ÷ 1 × (7/5) = **약 58일**
- 클라이언트 예상 기간: **90일**
- 차이: 산정 기간이 32일 짧음
- **판정**: 클라이언트 기간(90일) 그대로 사용 — 서두를 필요 없으며 1순위 "산출물 완성도" 기준 시 여유 시간을 디테일·QA에 투입

## 4. 포트폴리오 매칭

### 매칭 점수 (40% 기술 + 30% 도메인 + 20% 기능 + 10% 규모)

| Project | 기술 | 도메인 | 기능 | 규모 | 총점 |
|---------|-----|--------|-----|-----|-----|
| **EZ-Approve** | 30/40 (워드프레스 아니지만 어드민/CMS/RBAC 직결) | 25/30 (B2B SaaS) | 18/20 (CMS, N:N, 권한) | 9/10 | **82** |
| **Series-B** | 28/40 | 22/30 (B2B 포탈) | 19/20 (외부 API 다중 연동, 대시보드, 메타 관리) | 10/10 | **79** |
| **Harmony Link** | 25/40 | 25/30 (헬스케어 ≈ 생명과학 인접) | 16/20 (다양한 콘텐츠 유형) | 9/10 | **75** |

### 추천 근거
1. **EZ-Approve** — 워드프레스가 아닌 NestJS 기반이지만, 어드민 CMS 고도화 + N:N 관계(결재선 ↔ 사용자 ↔ 부서) + RBAC + 비개발자 운영자 UX 등 본 프로젝트의 핵심 요구와 직결
2. **Series-B** — 외부 API 다중 연동(KYC/감사/CRM)과 50+ 페이지 메타 정보 관리, 대시보드 구조가 Salesforce 연동·GA4 대시보드·SEO 메타에 직결
3. **Harmony Link** — 헬스케어(생명과학 인접 도메인) + 비IT 운영자(요양보호사·마케터) 직접 사용 UX + 6 플랫폼 동시 지원으로 반응형 경험

## 5. 최종 제안 요약

- **지원 금액**: **8,500,000원** (VAT 별도)
  - 산정: 1,000만원 × 85% = 850만원 (사용자 요청 비율 반영)
- **지원 기간**: **90일** (클라이언트 희망 기간 준수)
- **핵심 제안 포인트**:
  1. 참고 사이트 3건 직접 분석 → 응용분야 중심 IA + 자료실 4종 분류 + 3뷰 모드 + 브랜드/응용분야 필터 반영
  2. Astra Pro 경량 테마 + 자체 Custom Gutenberg Block 병행 → 운영 자율성 + Lighthouse 90+ 동시 확보
  3. ACF Pro Bidirectional Relationship → 제품 ↔ 응용분야 N:N 자동 양방향 연결
  4. Salesforce MCAE Web-to-Lead + reCAPTCHA v3 + 백업 저장 → 데이터 유실 0% 보장
  5. SEO + GEO 동시 최적화 (Schema.org JSON-LD + llms.txt + 의미 단위 콘텐츠 청크)
  6. 화상 교육 2회 + 영상 녹화본 + Notion 매뉴얼 → 마케팅팀 자율 운영 즉시 가능

## 6. 최종 산출물

(8단계 완료 후 추가)
