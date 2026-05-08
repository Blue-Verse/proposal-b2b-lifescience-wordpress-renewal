# B2B 생명과학 홈페이지 리뉴얼 및 워드프레스 구축 — 제안 분석 로그

> 생성일: 2026-05-08 (재생성)
> 공고 URL: https://www.wishket.com/project/155137/

## 1. 공고 파싱 결과

```yaml
job:
  title: "B2B 생명과학 홈페이지 리뉴얼 및 워드프레스 구축"
  category: "웹 자사몰 구축, 퍼블리싱·반응형 / 워드프레스 리뉴얼"
  budget_range: "800~1,000만 원 (상한 1,000만 원)"
  duration: "90일 (3~4개월 이내 완료 희망)"
  start: "계약 체결 후 즉시 시작"
  client_team: "PM 1명, 디자이너 1명"
  priority: ["산출물 완성도", "금액", "일정 준수"]
  tech_stack:
    - WordPress (Astra / Elementor / Bricks 등 빠른 테마 우대)
    - Bootstrap 5
    - ACF Pro
    - Salesforce MCAE (구 Pardot)
    - GA4 + GTM
    - SSL/HTTPS
    - SEO + GEO 최적화
  description: >
    생명과학 연구·분석 장비를 중심으로 한 공식 홈페이지 전면 리뉴얼.
    응용분야 중심 IA로 잠재 고객(Lead) 확보 및 세일즈 전환율 향상을 목표로 함.
    글로벌 기술 기업 수준의 전문적이고 신뢰감 있는 브랜드 이미지 구축.
    모바일 최적화, IA, CMS 고도화, CRM(Salesforce MCAE) 연동을 통한 데이터 기반 운영 체계.
  requirements:
    - 메뉴 구성도 기반 기획 고도화 (10개 카테고리)
    - UI/UX 디자인 (Minimal & Professional)
    - 워드프레스 기반 웹 개발 + 자식 테마 커스터마이징
    - 관리자페이지 개발 (CMS 커스터마이징)
    - 서버/DB/인프라 구성
    - 응용분야 페이지 Challenge → Solution → Reference → Product 스토리텔링 UI
    - 제품 ↔ 응용분야 N:N 자동 연결, 제품 → 자료실 → 응용분야 상호 연결
    - 자료실 4종(Document/News/Webinar/Video) + 브랜드/응용분야 필터
    - 통합 검색 (제품명/제목/본문/첨부 PDF)
    - PDF/이미지/Video 다운로드, 웨비나 다시보기, 팝업/프로모션
    - SEO/GEO 최적화, OG/메타태그/URL 커스텀
    - 문의 데이터 → Salesforce MCAE 자동 연동
    - GA4 방문자 분석 / 유입 경로 대시보드
    - 관리자 교육 + 운영 매뉴얼 제공
  client_questions:
    - "관리자 교육 및 운영 매뉴얼 제공이 가능한지"
    - "워드프레스 구축 시 주로 어떤 테마를 기반으로 커스터마이징하는지, 어느 수준까지 가능한지"
    - "B2B 기술 기업 홈페이지 구축 경험이 있는지, 유사 레퍼런스 공유 가능한지"
  deadline: "2026-05-21"
  job_post_url: "https://www.wishket.com/project/155137/"
  urls:
    - "https://www.cytivalifesciences.co.kr/"
    - "https://inside.lgensol.com/"
    - "https://service.chayon.co.kr/customer/reference-room"
  images: []
```

## 2. URL/이미지 분석

### 2.1 Cytiva Life Sciences Korea (https://www.cytivalifesciences.co.kr/)

- **IA 구조**: 브랜드(ÄKTA™ / Biacore™) → 응용분야(mAb / 바이러스벡터 / mRNA) → 제품 의 3계층 분류
- **응용 중심 마케팅**: "단일클론항체 제조 공정" 같은 워크플로우 중심 표현, 공정 단계별(배양→정제→여과) 솔루션 매칭
- **신뢰성 강화**: 글로벌 제약·바이오산업 지수 등 인사이트 제공, Danaher Trustmark 표시
- **멀티채널 접근**: 오프라인 데모 + 온라인 웨비나 + 정규 교육(Fast Trak™) 통합
- **컴플라이언스**: 의료기기 첨부문서(IFU) 별도 섹션, 기술 문서(RSD/MSDS/COA) 발급 시스템
- **UI 패턴**: 슬라이더 캐러셀, 카드형 제품 그리드, 검색+필터링, "참가 등록"/"자세히 보기" CTA

### 2.2 LG Energy Solution Inside / BATTERY INSIDE (https://inside.lgensol.com/)

- **콘텐츠 중심 IA**: News / Tech / Story / Opinion / Channel 5개 카테고리, 2차 분류 (Culture / Interview / About Us)
- **콘텐츠 디스커버리**: featured carousel + 최신 콘텐츠 + 20+ 카테고리 태그 기반 탐색
- **스토리텔링 UI**: 강한 헤드라인 + 부제, 카드 레이아웃, "자세히 보기" CTA
- **B2B 기술 콘텐츠 전략**: "배터리 배워보기" 난이도별 세분화, 글로서리 시리즈("배터리 용어사전")로 전문 용어 설명
- **타이포그래피**: 미니멀 + 충분한 화이트 스페이스, 무채색 + 시그니처 컬러 액센트, weight variation으로 위계 표현
- **참여 기능**: 뉴스레터 가입, 소셜 채널, "Battery Quiz" 게이미피케이션

### 2.3 자연과학 자료실 / reference-room (https://service.chayon.co.kr/customer/reference-room)

- **분류**: News(23) / Documents(43) / Webinar(32) / Video(3) / Others(2) 5종
- **브랜드 필터**: Anabios(22) / Eurofins Discovery(69) / AsedaSciences(6) / Cell Systems(4) / ACD(2)
- **디스플레이 모드**: Gallery / Magazine / List 3가지 전환
- **정렬**: 최신 / 조회수 (오름·내림)
- **검색**: 전문(Full-text) 검색 + 인기 키워드 추천 (Kinase / Obesity / GLP1 / Safety)
- **페이지네이션**: 1~5 페이지 + 다음 / 마지막 점프
- **콘텐츠 카드**: 썸네일 + 카테고리 태그 + 브랜드 + 제목
- **리드 게이트**: 자료 다운로드 시 PII 수집 팝업 (Lead Generation)

### 2.4 제안서 반영 사항

- **PRD에 반영**: Gallery / Magazine / List 디스플레이 모드, 인기 검색어 추천, 첨부 PDF 검색, 응용분야 페이지 Challenge → Solution → Reference → Product 스토리텔링 (Cytiva 패턴 기반)
- **견적·공수에 반영**: 자료실 다중 디스플레이 모드 + 다중 필터 BE 공수 1.5 M/D, ACF N:N 양방향 관계 BE 공수 2 M/D, 통합 검색 BE 공수 1.5 M/D
- **기술 스택 반영**: Relevanssi (전문 검색 + PDF 첨부 색인), Rank Math (SEO + 스키마), GeneratePress / Blocksy (속도 최적화 테마)
- **제안 포인트 반영**: 글로벌 B2B 기술 기업 사이트 분석 결과를 명시적으로 언급 — 분석 역량과 도메인 이해도 어필

## 3. 실현 가능성 분석 (내부용 — 클라이언트 노출 금지)

### 3.1 프로젝트 유형 분류
- **유형**: 풀스택 웹앱 (WordPress + ACF Pro + 외부 API 연동)
- **Feasibility**: 가능 (+15% 버퍼 — Salesforce MCAE 연동 보안 리뷰 시간)
- **AI 적합도**: FE 워드프레스 / BE 플러그인 / DevOps 모두 AI 시너지 영역

### 3.2 기본 공수 산정 (AI 보조 없이)

| 작업 | M/D | 비고 |
|------|-----|------|
| 기획 / IA / PRD / 와이어프레임 | 8 | 50+ 페이지, CPT/Taxonomy 모델 |
| Figma UI/UX 디자인 | 12 | 50+ 페이지 반응형 (PC/태블릿/모바일) |
| FE 워드프레스 | 18 | 테마 셋업 + 6개 핵심 템플릿 + 반응형 퍼블리싱 |
| BE 플러그인/연동 | 14 | CPT/검색/팝업/SEO/MCAE/GA4 |
| 인프라 / DevOps | 5 | 서버, SSL, CDN, 캐시 |
| QA + 마이그레이션 + 배포 | 8 | 통합 QA, 콘텐츠 마이그, 운영 배포 |
| 관리자 교육 + 매뉴얼 | 3 | 1회 교육 + PDF + 스크린캐스트 |
| **소계** | **68** | |

### 3.3 AI 절감률 적용 (가중평균 약 50%)

| 작업 | 기본 M/D | AI 절감률 | 조정 M/D |
|------|---------|----------|---------|
| 기획 | 8 | 35% | 5.2 |
| 디자인 | 12 | 15% | 10.2 |
| FE | 18 | 65% | 6.3 |
| BE | 14 | 55% | 6.3 |
| 인프라 | 5 | 65% | 1.75 |
| QA/배포/마이그 | 8 | 55% | 3.6 |
| 교육/매뉴얼 | 3 | 50% | 1.5 |
| **소계** | **68** | **~50%** | **~35** |

### 3.4 버퍼 적용 및 달력 일수
- 풀스택 웹앱 + Salesforce 연동 버퍼 +15%: 35 × 1.15 ≈ 40 M/D
- 1인 1일 기준 / 주 5일 → 40 ÷ 1 × (7/5) = 56일
- 클라이언트 커뮤니케이션 + 콘텐츠 입력 대기 등 운영 오버헤드 +15~20일 → 65~75일

### 3.5 판정
- 클라이언트 예상 기간: **90일**
- 내부 산정 기간: **65~75일**
- **판정: 충분한 여유 → 90일 그대로 채택**, 클라이언트 일정(3~4개월 이내) 안에 산출물 완성도(1순위) + 일정 준수(3순위) 동시 달성

## 4. 포트폴리오 매칭

매칭 기준: B2B 도메인 / 콘텐츠 관리 시스템 / 외부 CRM·API 연동 / 50+ 페이지 어드민 / 멀티테넌트.

| Project | 매칭 점수 | 핵심 매칭 근거 |
|---------|----------|---------------|
| **Series-B** | 95/100 | 외부 CRM/API 연동 (NICE KYC, ChatGPT) — Salesforce MCAE 폼 핸들러/API 연동에 그대로 적용. 50+ 페이지 어드민 포탈, 22 도메인 모듈, 권한 분리(RBAC) — 마케팅/콘텐츠/영업 사용자별 권한 설계 노하우. SEO 메타·다국어 호환 구조 경험. |
| **EZ-Approve** | 88/100 | 50+ 페이지 어드민 + 콘텐츠/조직/권한 관리 — 워드프레스 관리자 화면 커스터마이징(CPT/메타박스/권한)과 동일 패턴. 리치 에디터 + 미디어 라이브러리 — 자료실 관리에 적용. 운영자가 직접 콘텐츠를 편집할 수 있는 직관적 UI — 내부 마케팅팀 직접 운영 요구사항 부합. |
| **Harmony Link** | 80/100 | B2B 헬스케어 도메인의 콘텐츠 분류·자료 관리 노하우 — 생명과학 자료실(Document/News/Webinar/Video)에 적용. AI 분석(OpenAI) + 외부 API 연동 — SEO/GEO 콘텐츠 설계에 응용. 6 플랫폼 동시 운영 → PC/태블릿/모바일 반응형 안정성. |

**추천 순서**: Series-B (1순위 — 외부 CRM/API 연동 가장 유사) → EZ-Approve (2순위 — 어드민 CMS 커스터마이징) → Harmony Link (3순위 — B2B 도메인 콘텐츠 관리)

## 5. 최종 제안 요약

- **지원 금액**: 8,500,000원 (VAT 별도) — 클라이언트 상한 1,000만 원 × 0.85 (사용자 지정 — 금액 경쟁력 강화)
- **지원 기간**: 90일 — 클라이언트 예상 기간 그대로
- **핵심 제안 포인트**:
  1. 응용분야 중심 IA 재설계 (Cytiva 패턴) — 잠재 고객 여정 최적화
  2. 제품 ↔ 응용분야 ↔ 자료실 N:N 양방향 자동 연결 (ACF Pro)
  3. 통합 검색 (Relevanssi + 첨부 PDF + 다중 필터 + Gallery/List/Magazine 모드)
  4. Salesforce MCAE 폼 핸들러/REST API 연동 + UTM/GA Client ID/Referrer 어트리뷰션
  5. SEO + GEO 동시 최적화 (JSON-LD 스키마 + llms.txt + OG/메타)
  6. GeneratePress/Blocksy + Bricks/Elementor Pro + 자체 PHP 템플릿 — 속도와 운영성 동시 달성
  7. 유사 B2B 콘텐츠 관리 / 외부 CRM 연동 다수 경험 → 90일 내 완성도 보장

- **클라이언트 사전 검증 질문 답변 요지**:
  - Q1 관리자 교육 / 운영 매뉴얼 → **가능**, 1회 교육 + PDF + 스크린캐스트 영상 제공
  - Q2 워드프레스 테마 / 커스터마이징 수준 → GeneratePress / Blocksy / Astra Pro 기반 + Bricks Builder 또는 Elementor Pro, 핵심 템플릿은 자식 테마 + ACF Pro + 자체 PHP로 페이지 빌더 오버헤드 없이 빠르게 동작
  - Q3 B2B 기술 기업 홈페이지 경험 → Series-B (VC 펀드 포탈) / EZ-Approve (전자결재 SaaS) / Harmony Link (헬스케어 SaaS) 등 B2B 콘텐츠·관리자 시스템 다수 경험


## 6. 최종 산출물 (8단계 출력 전문)

### 6.1 제안서 사이트 URL
https://proposal-router.claude-ai-b27.workers.dev/proposal-b2b-lifescience-wordpress-renewal/

### 6.2 지원 금액
8,500,000원 (VAT 별도)

산정 근거: 클라이언트 예상 금액 상한(1,000만 원) × 0.85, VAT 별도. 사용자 지정 — 금액 경쟁력(2순위)을 강화하면서도 산출물 완성도(1순위)를 위한 충분한 공수 확보.

### 6.3 지원 기간
90일

기간 근거: 클라이언트 예상 기간 그대로 채택. Phase 1 IA/PRD(2주) → Phase 2 Figma 디자인(3주) → Phase 3 워드프레스 개발+연동(5주) → Phase 4 마이그/QA(2주) → Phase 5 배포·교육(1주). 유사 프로젝트 수행 경험 기반 효율적 진행.

### 6.4 클라이언트 질문 답변

**Q1: 향후 내부 마케팅팀이 직접 콘텐츠를 운영할 수 있도록 관리자 교육 및 운영 매뉴얼 제공이 가능한지 문의드립니다.**

가능합니다. 비개발자가 직접 운영할 수 있는 수준으로 다음을 제공합니다.
- 관리자 교육 1회 (Zoom 또는 대면, 약 2시간) — 제품·응용분야·자료실 등록, 팝업·SEO 메타 관리, 문의/리드 모니터링, GA4 대시보드 사용법
- 운영 매뉴얼 PDF — 화면 캡처 기반 단계별 가이드 (등록 → 매핑 → 발행 → 점검)
- 운영 매뉴얼 스크린캐스트 영상 — 핵심 시나리오별 영상(5~7편, 시나리오당 2~5분)
- 1개월 무상 하자 보수 기간 동안 운영 중 발생하는 문의 대응
- ACF Pro / 페이지 빌더 / Rank Math 등의 직관적 인터페이스 활용으로 코드 수정 없이 콘텐츠 운영 가능

**Q2: 워드프레스 구축 시 주로 어떤 테마를 기반으로 커스터마이징하여 사용하시는지, 또한 어느 수준까지 커스터마이징이 가능한지 문의드립니다.**

페이지 로딩 속도(Core Web Vitals)와 운영성을 고려해 다음 조합을 권장합니다.
- 베이스 테마: GeneratePress / Blocksy / Astra Pro 등 경량·고속 테마 (모두 자식 테마 커스터마이징 경험 보유)
- 페이지 빌더: Bricks Builder 또는 Elementor Pro — 비개발자 콘텐츠 편집용
- 핵심 템플릿(제품 카테고리 / 제품 상세 / 응용분야 / 자료실)은 자식 테마 + ACF Pro + 자체 PHP 템플릿으로 직접 구현 → 페이지 빌더 오버헤드 없이 빠르게 동작
- 커스터마이징 수준
  - CPT(커스텀 포스트 타입) / Taxonomy / 메타박스 자유 설계
  - ACF Pro 양방향 관계로 제품 ↔ 응용분야 ↔ 자료실 N:N 자동 연결
  - 통합 검색(Relevanssi / ElasticPress) — 본문·첨부 PDF·필터링 커스터마이징
  - REST API 연동, 외부 시스템(Salesforce MCAE / GA4) 자동 연결
  - 관리자 메뉴 / 권한 / 메타박스 / 미디어 라이브러리 UI 커스터마이징
  - JSON-LD 스키마 / OG / sitemap.xml / llms.txt(GEO) 자동 생성 로직 추가

**Q3: B2B 기술 기업 홈페이지 구축 경험이 있는지, 유사한 레퍼런스를 공유해주실 수 있는지 문의드립니다.**

B2B 도메인의 콘텐츠 관리 시스템 / 어드민 포탈 / 외부 CRM·API 연동 프로젝트를 다수 수행하였습니다.
- Series-B (VC 펀드 관리 플랫폼) — 50+ 페이지 어드민 포탈, 22 도메인 모듈 권한 분리, 외부 시스템 연동(NICE KYC, ChatGPT API 기반 보고서 자동 생성). Salesforce MCAE 폼 핸들러/REST API 연동에 동일 패턴 적용 가능.
- EZ-Approve (전자결재 SaaS) — 50+ 페이지 어드민, 7 사용자 역할(RBAC), 6계층 보안, Lexical 리치 에디터(170 파일/26 커스텀 노드) 및 미디어 라이브러리 — 자료실(Document/News/Webinar/Video) 관리에 그대로 적용.
- Harmony Link (시니어 주간보호 B2B SaaS) — 멀티테넌트 아키텍처, 6 플랫폼 동시 지원(133K+ LOC, 140+ API), AI 분석(OpenAI) 연동, 자료/알림 관리 — B2B 도메인 콘텐츠 관리 노하우.

3개 프로젝트의 자세한 내용은 위 제안서 사이트의 "유사 프로젝트 경험" 페이지 또는 위시켓 포트폴리오에서 확인하실 수 있습니다.

### 6.5 지원 내용 (전체 텍스트)

```
안녕하세요, B2B 생명과학 홈페이지 리뉴얼 및 워드프레스 구축 프로젝트에 지원합니다.

본 프로젝트에 대한 상세 제안서(견적서, 공수계산서, PRD, 일정, 포트폴리오)를 별도 페이지로 준비하였습니다. 아래 링크에서 확인해 주시면 감사하겠습니다.
▶ 제안서 상세 페이지: https://proposal-router.claude-ai-b27.workers.dev/proposal-b2b-lifescience-wordpress-renewal/
▶ 위시켓 포트폴리오: https://www.wishket.com/partners/p/blueverse1/

---

<프로젝트 진행 제안>

■ 프로젝트 분석
- 단순 기업 소개가 아닌 응용분야 중심 IA로 재구성 — Cytiva·LG에너지솔루션 Inside 등 글로벌 B2B 기술 기업 사이트 분석을 토대로 Challenge → Solution → Reference → Product 스토리텔링 흐름 적용
- 제품 ↔ 응용분야 ↔ 자료실 N:N 양방향 자동 연결 (ACF Pro Bidirectional Relationship + 공통 Taxonomy) — 운영자가 한 번만 매핑하면 양쪽 페이지에서 자동 노출
- 자료실(Document/News/Webinar/Video) — 자연과학 reference-room 패턴 참고하여 브랜드/응용분야 다중 필터, Gallery/Magazine/List 디스플레이 모드, 인기 검색어 추천, 첨부 PDF 통합 검색 구현
- Salesforce MCAE(구 Pardot) 자동 연동 — 모든 폼(데모/세미나/웨비나/문의)을 Form Handler 또는 REST API로 연동, UTM·Referrer·GA Client ID까지 함께 전송하여 어트리뷰션 정확화
- SEO + GEO 동시 최적화 — JSON-LD 스키마(Article/FAQ/HowTo/Product), sitemap.xml, robots.txt, llms.txt까지 적용해 ChatGPT/Gemini/Perplexity 등 생성형 검색 엔진 노출 가능성 확보
- 속도 우선 — GeneratePress/Blocksy/Astra Pro + Bricks/Elementor Pro 조합 + 핵심 템플릿은 자식 테마 + ACF Pro + 자체 PHP로 페이지 빌더 오버헤드 제거

■ 작업 일정

[Phase 1: 킥오프 / IA·PRD 고도화] Day 1–14 (2주)
- 클라이언트 메뉴 구성도 기반 IA 고도화, 50+ 페이지 와이어프레임, CPT/Taxonomy/관계 데이터 모델 설계, Salesforce MCAE 연동 스펙 확정

[Phase 2: Figma UI/UX 디자인] Day 15–35 (3주)
- Minimal & Professional 디자인 시스템(컬러/타이포/컴포넌트), 50+ 페이지 반응형 시안 (PC/태블릿/모바일)

[Phase 3: 워드프레스 개발 + 외부 연동] Day 36–70 (5주)
- 테마 셋업 → 핵심 템플릿(제품/응용분야/자료실) 커스터마이징 → 통합 검색 / 팝업 / SEO 메타 / Salesforce MCAE / GA4·GTM 구현 → 알파(Day 56) → 베타(Day 70)

[Phase 4: 콘텐츠 마이그레이션 + 통합 QA] Day 71–83 (약 2주)
- 스테이징 콘텐츠/미디어 마이그레이션, 크로스 브라우저/디바이스 QA, 코어 웹 바이탈 튜닝, 폼/MCAE 연동 시나리오 검증

[Phase 5: 운영 배포 + 관리자 교육] Day 84–90 (1주)
- 운영 환경 배포 / DNS 전환, 검색엔진 색인 등록, 관리자 교육 1회, 운영 매뉴얼(PDF + 스크린캐스트) 전달

■ 마일스톤 및 산출물
- M1 (Day 14): IA / PRD / 사이트맵 / 와이어프레임 확정
- M2 (Day 28): 1차 디자인 시안
- M3 (Day 35): 최종 디자인 시안 (50+ 페이지 반응형)
- M4 (Day 56): 알파 빌드 — 핵심 템플릿 동작 확인
- M5 (Day 70): 베타 빌드 + Salesforce MCAE 연동 검증
- M6 (Day 83): QA 완료 (코어 웹 바이탈 / 보안 점검 통과)
- M7 (Day 90): 운영 배포 + 관리자 교육 + 매뉴얼 전달

■ 미팅 시 협의 필요 사항
- 호스팅 환경 (Cloudways / WP Engine / 국내 매니지드 워드프레스 등 권장 옵션 또는 기존 환경)
- 다국어 확장 시점 (한국어 단일 vs 영문 동시) 및 WPML / Polylang 선택
- Salesforce MCAE 인증 방식 (Form Handler vs REST API + Connected App) 및 시운영 단계 캠페인 매핑
- 콘텐츠 마이그레이션 범위 (기존 사이트 전체 / 일부 / 신규 작성) 및 데이터 제공 방식
- 유료 플러그인/테마 라이선스(Bricks / Elementor Pro / Rank Math Pro / ACF Pro) 분담 방식

---

<유사 프로젝트 진행 경험>

▶ Series-B (2023.11~2024.12, 14개월)
- 프로젝트 유형: VC 펀드 관리 플랫폼 (B2B 포탈 / 핀테크)
- 핵심 기능: 50+ 페이지 멀티테넌트 어드민, 22 도메인 모듈, 80+ 엔티티, 200+ API 엔드포인트, NICE KYC + ChatGPT API 연동, VICS 규제 5종 자동 생성, Lexical + Yjs CRDT 실시간 공동편집
- 유사점: 외부 CRM/API 연동 경험 → Salesforce MCAE 폼 핸들러/REST API 연동에 동일 적용. 50+ 페이지 어드민 + 권한 분리(RBAC) → 마케팅/콘텐츠/영업 사용자별 권한 설계 노하우. SEO 메타·다국어 호환 구조 경험
- 기술 스택: Next.js 13, NestJS 10, MySQL, AWS, External API 다수 연동

▶ EZ-Approve (2026.01~2026.03, 약 9주)
- 프로젝트 유형: 전자결재 SaaS (B2B SaaS / 어드민 포탈)
- 핵심 기능: 50+ 페이지 어드민, 7 사용자 역할(RBAC), 6계층 보안, Lexical 리치 에디터(170 파일, 26 커스텀 노드), 토큰 기반 외부 셀프서비스 포탈, 다국어
- 유사점: 대규모 CMS / 어드민 커스터마이징 — 워드프레스 관리자 화면 커스터마이징(CPT/메타박스/권한/미디어)과 동일 패턴. 리치 에디터 + 미디어 라이브러리 → 자료실(Document/News/Webinar/Video) 관리에 적용. 운영자가 직접 콘텐츠를 편집할 수 있는 직관적 UI
- 기술 스택: NestJS 10, Next.js 13, TypeScript, MySQL 8, Lexical/Yjs, CASL (RBAC)

▶ Harmony Link (2025, 약 6개월)
- 프로젝트 유형: 시니어 주간보호 B2B SaaS (헬스케어)
- 핵심 기능: 6 플랫폼 동시 지원, 멀티테넌트 아키텍처, 133K+ LOC, 140+ API, 케어 로그/투약/AI 건강 분석(OpenAI), 전자서명, 자료실/알림
- 유사점: B2B 도메인 콘텐츠 분류·자료 관리 노하우 → 생명과학 자료실 적용. AI + 외부 API 연동 → SEO/GEO 콘텐츠 설계 응용. 6 플랫폼 운영 → PC/태블릿/모바일 반응형 안정성
- 기술 스택: Flutter, NestJS, Next.js, MySQL, AWS CDK, OpenAI

---

<사용 기술과 툴>

▶ 개발 기술
- WordPress 6.x · GeneratePress / Blocksy / Astra Pro · Bricks Builder / Elementor Pro
- ACF Pro (양방향 관계 / N:N 자동 연결)
- Bootstrap 5 · PHP 8.x · MySQL 8
- Relevanssi (통합 검색 + 첨부 PDF 색인) · Rank Math (SEO + 스키마)
- Salesforce MCAE (Form Handler / REST API) · GA4 + GTM
- Cloudflare (CDN/WAF) · LiteSpeed Cache · JSON-LD 스키마 · llms.txt (GEO)

▶ 개발 도구 및 인프라
- 버전 관리: GitHub
- CI/CD: GitHub Actions (테마/플러그인 자동 배포)
- 호스팅: Cloudways / WP Engine / 국내 매니지드 워드프레스 (협의)
- 컨테이너: Docker (로컬/스테이징)

▶ 커뮤니케이션
- 일일 진행 공유: Slack 또는 카카오톡
- 주간 미팅: Zoom / Google Meet
- 문서 공유: Notion 또는 Google Docs
- 이슈 트래킹: GitHub Issues
```

### 6.6 관련 포트폴리오 추천 (위시켓 폼 입력용)

1. **Series-B** — VC 펀드 관리 플랫폼: 외부 CRM/API 연동(NICE KYC, ChatGPT) 경험은 Salesforce MCAE 연동의 직접적 레퍼런스. 50+ 페이지 어드민 포탈 + 권한 분리(RBAC) → 마케팅/콘텐츠/영업 사용자별 권한 설계 노하우.
2. **EZ-Approve** — 전자결재 SaaS: 대규모 CMS / 어드민 커스터마이징 + 리치 에디터 + 미디어 라이브러리 — 자료실(Document/News/Webinar/Video) 관리 및 워드프레스 관리자 커스터마이징에 직접 적용.
3. **Harmony Link** — 시니어 주간보호 SaaS: B2B 도메인 콘텐츠 관리 + AI/외부 API 연동 + 6 플랫폼 동시 운영 경험 — 생명과학 자료실 / SEO·GEO 설계 / PC·태블릿·모바일 반응형 안정성에 적용.
