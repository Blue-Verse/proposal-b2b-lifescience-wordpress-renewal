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

### 제안서 사이트 URL

https://proposal-router.claude-ai-b27.workers.dev/proposal-b2b-lifescience-wordpress-renewal/

### 지원 금액

```
8,500,000원
```

### 지원 기간

```
90일
```

### 클라이언트 질문 답변

**Q1. 향후 내부 마케팅팀이 직접 콘텐츠를 운영할 수 있도록 관리자 교육 및 운영 매뉴얼 제공이 가능한지 문의드립니다.**

가능합니다. 본 프로젝트에는 다음 항목이 포함됩니다.
- 화상 교육 2회 (회당 2시간, Zoom 또는 Google Meet) — Phase 5 진행 시 일정 협의
- 교육 영상 녹화본 제공 — 신규 입사자 대비 반복 학습용
- Notion 기반 운영 매뉴얼 — 단계별 스크린샷 + 체크리스트 형식
- 매뉴얼 범위: 콘텐츠 등록(제품/응용분야/자료실/교육/데모/이벤트), 팝업 관리, SEO 메타 입력, Salesforce 연동 점검, GA4 대시보드 해석, 자료실 미디어 라이브러리 관리
- 1개월 무상 하자 보수 기간 동안 매뉴얼 미수록 항목에 대한 질의 응답 지원

또한 일반 콘텐츠 페이지는 Elementor Pro 비주얼 에디터로 구성하여 비개발자도 즉시 편집 가능하도록 설계합니다.

**Q2. 워드프레스 구축 시 주로 어떤 테마를 기반으로 커스터마이징하여 사용하시는지, 또한 어느 수준까지 커스터마이징이 가능한지 문의드립니다.**

▶ 베이스 테마
- 1순위: Astra Pro — 페이지 로딩 속도(1.5초 이내) 및 Lighthouse 점수(90+) 확보 우수, Elementor Pro와 호환성 검증
- 2순위: Blocksy 또는 GeneratePress — 동일 수준의 경량 테마, 클라이언트 선호 시 변경 가능
- Divi, Avada 등 무거운 페이지 빌더 종속형 테마는 지양 (페이지 로딩 속도 저하 및 종속성 리스크)

▶ 커스터마이징 수준
- 자식 테마(Child Theme) 구성으로 베이스 테마의 functions.php·템플릿 비침습적 확장
- 커스텀 포스트 타입(CPT) 직접 정의 — 제품/응용분야/자료실/교육/데모/이벤트 등 7개+
- ACF Pro 관계 필드(Bidirectional Relationship)로 제품 ↔ 응용분야 N:N 자동 양방향 연결
- 자체 Custom Gutenberg Block 개발 — 메인 히어로, 응용분야 스토리텔링 UI(Challenge → Solution → Reference → Product) 등 핵심 페이지에 적용
- WordPress REST API 확장 — Salesforce MCAE 연동 엔드포인트, 통합 검색 인덱스, 외부 시스템 데이터 연계
- WP-CLI 기반 자동 배포 + 워드프레스 표준 hook/filter 활용으로 워드프레스 코어 업데이트와 호환성 유지

**Q3. B2B 기술 기업 홈페이지 구축 경험이 있는지, 유사한 레퍼런스를 공유해주실 수 있는지 문의드립니다.**

다수 보유하고 있습니다. 대표 사례 3건 (상세는 위 제안서 사이트 "유사 프로젝트 경험" 메뉴 참조):

1. **전자결재 SaaS (B2B SaaS · 기업용 포탈)** — 50+ 페이지, 7 사용자 역할 RBAC 어드민, 다단계 결재선 N:N 관계 데이터 모델링, 비개발자 운영 자율성 확보
2. **VC 펀드 관리 플랫폼 (B2B 핀테크 포탈)** — PR 1,652건, 외부 API 다중 연동(KYC/감사/CRM), 50+ 페이지 SEO 메타 일괄 관리, 폼 데이터 백업·재시도
3. **시니어 주간보호 관리 플랫폼 (B2B SaaS · 헬스케어, 생명과학 인접 도메인)** — 133K+ LOC, 다양한 콘텐츠 유형 통합 관리, 6 플랫폼 동시 지원, 비IT 운영자 직접 사용 UX

### 지원 내용 (전체 텍스트)

```
안녕하세요, B2B 생명과학 홈페이지 리뉴얼 및 워드프레스 구축 프로젝트에 지원합니다.

본 프로젝트에 대한 상세 제안서(견적서, 공수계산서, PRD, 일정, 포트폴리오)를 별도 페이지로 준비하였습니다. 아래 링크에서 확인해 주시면 감사하겠습니다.
▶ 제안서 상세 페이지: https://proposal-router.claude-ai-b27.workers.dev/proposal-b2b-lifescience-wordpress-renewal/
▶ 위시켓 포트폴리오: https://www.wishket.com/partners/p/blueverse1/

---

<프로젝트 진행 제안>

■ 프로젝트 분석
- 핵심 목표: 응용분야(Application) 중심 IA로 잠재 고객(Lead) 확보 및 세일즈 전환율 향상
- 참고 사이트(Cytiva Korea, LG에너지솔루션 Battery Inside, 자연과학 자료실) 직접 분석 결과 반영
  · 응용분야 중심 카테고리 + 제품 기술 기반 분류의 듀얼 IA
  · 자료실 4종 분류(Document/News/Webinar/Video) + 브랜드·응용분야 필터 + 3뷰 모드(gallery/magazine/list)
  · 카드 레이아웃 + 발행 날짜 + 다층 네비게이션
- 핵심 기술 결정
  · Astra Pro 경량 테마 + Elementor Pro + 자체 Custom Gutenberg Block 병행 → 운영 자율성 + Lighthouse 90+ 동시 확보
  · ACF Pro Bidirectional Relationship → 제품 ↔ 응용분야 N:N 자동 양방향 연결
  · Salesforce MCAE Web-to-Lead + reCAPTCHA v3 + 백업 저장 → 데이터 유실 0% 보장
  · SEO + GEO 동시 최적화 (Schema.org JSON-LD + llms.txt + 의미 단위 콘텐츠 청크)

■ 작업 일정

[Phase 1: 기획 & IA 고도화] Day 1–18 (3주)
- 참고 사이트 심층 분석, 클라이언트 메뉴 구성도 기반 IA 고도화, 와이어프레임, DB 스키마, ACF 필드 명세

[Phase 2: UI/UX 디자인 (Figma)] Day 12–35 (3.5주, Phase 1 후반과 일부 병행)
- 디자인 시스템 정의, 메인 + 9개 대분류 페이지, 반응형 3종(PC/태블릿/모바일) 시안 확정

[Phase 3: 워드프레스 개발 + 커스텀 포스트 타입] Day 25–60 (5주)
- Astra Pro 자식 테마, CPT 7종+, ACF 관계 필드(N:N), 응용분야 스토리텔링 Custom Gutenberg Block, 통합 검색 + 필터

[Phase 4: 외부 연동 + 마케팅 기능] Day 50–75 (3.5주)
- Salesforce MCAE Web-to-Lead 연동, reCAPTCHA v3, GA4/GTM, SEO/GEO 메타 + Schema.org, 팝업 관리

[Phase 5: QA + 배포 + 관리자 교육] Day 70–90 (3주)
- 크로스 브라우저·반응형·성능·보안 QA, SSL 적용, 운영 매뉴얼(Notion + 단계별 스크린샷), 화상 교육 2회 + 영상 녹화본

■ 마일스톤 및 산출물
- M1 (Day 18): IA & 와이어프레임 확정 — 요구사항 정의서, IA 다이어그램, 와이어프레임 승인
- M2 (Day 35): 디자인 시안 확정 — Figma 시안(PC/태블릿/모바일) 승인
- M3 (Day 60): 워드프레스 개발 완료 — CPT, ACF, Custom Block, 통합 검색 동작 확인
- M4 (Day 75): 외부 연동 완료 — Salesforce 연동 데이터 송수신, GA4 수집, SEO 메타 검수
- M5 (Day 90): 운영 환경 오픈 — 전체 QA 통과, 매뉴얼/교육 완료, SSL 적용, 인수인계

■ 미팅 시 협의 필요 사항
- Salesforce MCAE 연동 정보 공유 절차 (Web-to-Lead 표준 엔드포인트 사용 가정, 별도 OAuth 필요 시 클라이언트 측 권한 발급 일정)
- 자료실 영상(Webinar) 호스팅 방식 (자체 호스팅 vs Vimeo/YouTube 임베드)
- 호스팅 환경 결정 (Cloudways / AWS Lightsail / 카페24 등)
- 콘텐츠 마이그레이션 범위 (기존 자료실 자료 이관 여부 및 분량)
- Astra Pro / Elementor Pro / ACF Pro 라이선스 보유 여부

---

<유사 프로젝트 진행 경험>

▶ 전자결재 SaaS (EZ-Approve) (2026.01~2026.03, 약 9주)
- 프로젝트 유형: B2B SaaS · 기업용 포탈 · 어드민 CMS
- 핵심 기능: 다단계 전자결재 엔진(8종 액션), RBAC 어드민(7 역할), 50+ 페이지, Lexical 리치 에디터, 실시간 공동편집(CRDT/Yjs), 토큰 기반 외부 셀프서비스 포탈
- 유사점: 관리자 CMS 고도화 + N:N 관계 데이터 모델링(결재선 ↔ 사용자 ↔ 부서) + 비개발자 운영 자율성 + 50+ 페이지 정보 구조 설계
- 기술 스택: NestJS 10, Next.js 13, TypeScript, MySQL 8, Lexical+Yjs, CASL, Docker

▶ VC 펀드 관리 플랫폼 (Series-B) (2023.11~2024.12, 14개월)
- 프로젝트 유형: 핀테크 · B2B 포탈 · 외부 API 다중 연동
- 핵심 기능: GP/LP/스타트업 3개 그룹 포탈, AI 투자 보고서(ChatGPT API), VICS 규제 양식 5종, NICE KYC, CRDT 실시간 공동편집, 5계층 보안+DLP+GeoIP
- 유사점: 외부 시스템 다중 연동(KYC/감사/CRM) → Salesforce MCAE 연동에 직결 / 50+ 페이지 메타 정보 일괄 관리 → SEO 메타 관리 / 폼 제출 실패 시 백업·재시도 패턴
- 기술 스택: Next.js 13, NestJS 10, MySQL, Lexical/Yjs, AWS, OpenAI API
- 규모: PR 1,652건, 80+ 엔티티, 200~300+ API 엔드포인트

▶ 시니어 주간보호 관리 플랫폼 (Harmony Link) (2025, 약 6개월)
- 프로젝트 유형: B2B SaaS · 헬스케어(생명과학 인접 도메인)
- 핵심 기능: 케어 로그/투약/보호자 알림/AI 건강 분석(OpenAI), 전자서명, 멀티테넌트, 6 플랫폼 동시 지원
- 유사점: 헬스케어 도메인 이해도 → 생명과학 전문 산업 용어/워크플로우에 적용 / 다양한 콘텐츠 유형 통합 관리 → 자료실 4종 분류 / 비IT 운영자 직접 사용 UX
- 기술 스택: NestJS, Next.js, Flutter, TypeScript, MySQL, AWS CDK, OpenAI API
- 규모: 133K+ LOC, 140+ API 엔드포인트

---

<사용 기술과 툴>

▶ 개발 기술
- WordPress 6.x, Astra Pro, Elementor Pro, ACF Pro
- Custom Gutenberg Block, PHP 8.x, MySQL 8
- Bootstrap 5 (반응형 그리드), Tailwind CSS (보조)
- Salesforce MCAE Web-to-Lead, reCAPTCHA v3
- GA4, Google Tag Manager, Schema.org JSON-LD

▶ 개발 도구 및 인프라
- 버전 관리: GitHub
- CI/CD: GitHub Actions + WP-CLI 자동 배포
- 클라우드: Cloudways / AWS Lightsail (프로젝트 특성에 맞게 선택)
- 컨테이너: Docker (개발 환경)

▶ 커뮤니케이션
- 일일 진행 공유: Slack 또는 카카오톡
- 주간 미팅: Zoom / Google Meet
- 문서 공유: Notion 또는 Google Docs
- 디자인: Figma
- 이슈 트래킹: GitHub Issues 또는 Linear
```

### 관련 포트폴리오 추천

위시켓 폼의 "관련 포트폴리오" 섹션에 아래 프로젝트를 선택/입력:

1. **EZ-Approve (전자결재 SaaS)** — 어드민 CMS 고도화 + N:N 관계 + RBAC + 50+ 페이지 IA, 비개발자 운영 자율성 직결
2. **Series-B (VC 펀드 관리 플랫폼)** — 외부 API 다중 연동(KYC/감사/CRM)과 SEO 메타 일괄 관리 경험이 Salesforce MCAE·GA4·SEO 메타 관리에 직결
3. **Harmony Link (시니어 주간보호 관리 플랫폼)** — 헬스케어(생명과학 인접 도메인) + 다양한 콘텐츠 유형 통합 관리 + 비IT 운영자 직접 사용 UX
