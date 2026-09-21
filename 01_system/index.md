# GUNG:ON Project Index

## 프로젝트

궁온 / GUNG:ON
페르소나 체험형 경복궁 관람 시스템

---

# 현재 최종 서비스 구조

## 핵심 터치포인트

### WEB
안내 · 현황 · 기록

### SMART GLASS
선택 · 관람 · 해석

### INTERACTIVE SCREEN
행동 · 체험

## 선택형 확장

### CUSTOM GOODS
개인화 · 선택 구매 · 관람 후 리마인드

---

# Persona

- 왕
- 왕비
- 세자

페르소나 선택은 Smart Glass에서만 진행한다.

---

# Smart Glass 핵심 경험

## Persona-based Interpretation
누구의 시선으로 볼 것인가

## Historical Event
이 공간에서 무슨 일이 있었는가

## Focus Point
무엇을 주목해서 볼 것인가

Smart Glass는 1인칭 시점으로 고정한다.

---

# Interactive Screen Program

## 오늘의 수라상

## 훈민정음 서재

대표 프로그램은 위 2개만 사용한다.

---

# Web

## 이용 안내
- 서비스 안내
- 이용 방법
- 언어 / 접근성

## 관람 현황
- 현재 페르소나 확인
- 프로그램 진행 상태
- 프로그램 완료 상태

## 관람 기록
- 완료 프로그램
- 프로그램 결과
- 나의 관람 기록

## 선택형 확장
- 커스텀 굿즈 미리보기
- 선택 구매

---

# 사용하지 않는 기능

아래 기능은 현재 최종 기획에서 사용하지 않는다.

- Web ↔ Smart Glass 연결
- Smart Glass 연결 상태
- GPS
- 지도 기반 Web
- AI 동선 추천
- Digital Stamp
- 실물 엽전
- 무료 굿즈
- 3인칭 Smart Glass
- 왕 / 왕비 / 세자 외 Persona

---

# Custom Goods

커스텀 굿즈는 체험 보상이 아니다.

사용자가 원하는 경우
Persona와 Program Result를 반영한 개인화 상품을 직접 구매한다.

목적은 관람 이후에도 경험을 일상에서 다시 떠올리게 하는 것이다.

NFC 기반 기록 재열람은 현재 핵심 기능으로 확정하지 않는다.

---

# AI Principle

AI는 역사적 사실을 임의로 생성하지 않는다.

전문가가 검수한 역사 콘텐츠를 기반으로

- 선택
- 구성
- 표현 방식 조정
- 우선순위 조정

을 담당한다.

---

# Presentation

01 시스템 기획은 메인 발표에서 5장으로 구성한다.

1. 문제 정의 + 프로젝트 방향
2. 선택과 집중 + 최종 구조
3. 터치포인트 역할 + 전체 경험 흐름
4. 핵심 현장 경험
5. 관람 전 · 중 · 후 연결

**대제목(H1) 폰트 크기 — 레이아웃 템플릿별로 분리(2026-09-07 확정, CHANGE 24)**: 1번 레이아웃(좌측텍스트형) 56px / 2번 레이아웃(상단전체폭타이틀형) 44px, 둘 다 ExtraBold. 부제/본문은 20px Medium #595959 공통. 이 크기 규칙은 새로 만드는 슬라이드에만 적용하고, 이미 만들어진 기존 슬라이드는 이 규칙으로 되돌리지 않는다.

---

# Branding

Brand Essence:
Perspective / 시선

Main Slogan:
시선을 켜면, 궁이 달라진다.

현재 컬러 방향:
오방색 + 경복궁 실제 물성 → 현대적인 Color System

재질 모티브:
WOOD 중심
STONE은 대표 재질 모티브에서 제외/축소 — **확정됨**(03_GUNGON_Reference_DesignMethod_STEP3.md 섹션 13). 단, Color System의 Neutral Color 토큰 `STONE #6E6B61`은 그대로 유지한다 — "대표 재질 모티브"와 "컬러 토큰"은 별개 개념. Figma 색상 정의 슬라이드(S22/S23)의 8 Base Color 팔레트 자체는 바꿀 필요 없음.

---

# 파일 목록 (Full Index)

**이 목록은 실제 파일 시스템과 항상 100% 일치해야 한다.** 파일을 추가/이동/이름변경/삭제할 때마다 반드시 여기도 같이 고친다(자세한 규칙은 `RULE.md` 참고).

마지막 확인: 2026-09-21 (`find`로 직접 대조함 — `04_Branding/GUNG-ON_굿즈_섹션_정리_ver 1.0.md` 신규 반영)

```text
GUNG ON/
├─ 01_system/
│  ├─ index.md          ← 이 파일
│  ├─ log.md             변경 로그
│  └─ RULE.md            운영 규칙(목적/폴더구조/작성원칙/파일명·링크 규칙)
│
├─ 02_Service_Design/
│  ├─ GUNGON_Service_Planning_VER 1.0.md     서비스 기획 v1.0
│  ├─ GUNGON_Service_Planning_VER 2.0.md     서비스 기획 v2.0 (2026-09-12)
│  └─ GUNGON_Service_Planning_VER_2.1.md     서비스 기획 v2.1 (2026-09-12, 현재 최신)
│
├─ 03_IA/
│  └─ GUNGON_IA_VER 1.0.md                 정보구조도 (유일 문서)
│
├─ 04_Branding/
│  ├─ GUNGON_Branding_VER 1.0.md    전체 요약 Master
│  ├─ GUNG-ON_굿즈_섹션_정리_ver 1.0.md   Figma 굿즈 섹션(node 2337:1533) 내용 정리 (2026-09-21 신규)
│  ├─ 01_STEP/
│  │  ├─ 01_GUNGON_Brand_Strategy_STEP1.md
│  │  ├─ 02_GUNGON_Naming_Verbal_STEP2.md
│  │  ├─ 03_GUNGON_Reference_DesignMethod_STEP3.md
│  │  ├─ 04_GUNGON_Brand_Moodboard_STEP4.md
│  │  └─ 05_GUNGON_Color_Origin_STEP5.md
│  │     (STEP06 Color System 상세본은 아직 없음)
│  └─ 00_Index/
│     └─ 페르소나체험형_경복궁관람시스템_브랜딩_가이드_v1_0.md   STEP1~12 체크리스트 (2026-09-08 수정됨)
│
├─ 05_Presentation/   (비어있음)
│
├─ 06_research/       (예전 `05_research` — 05 번호 중복을 해소하려고 06으로 리네임됨)
│  └─ Brand Moodboard Reference.md      무드보드 레퍼런스 원본
│
└─ 07_raw/            원본/작업 중 문서 보관(정제 전 raw). 2026-09-12 신설
   └─ 3주차/
      ├─ GUNG ON 검증 파트.md            현장 인사이트 정합성 검증 + 프로토타입 사용자 검증
      ├─ 서비스디자인 보완서.md            서비스 원칙·시나리오·터치포인트 연결성·블루프린트
      └─ 01_3주차 전체 기획 정리/
         ├─ 3주차 전체 기획 정리 _ver.1.0.md
         ├─ 3주차 전체 기획 정리 VER 2.0.md
         ├─ 3주차 전체 기획 정리 VER 2.1.md
         └─ 3주차 전체 기획 정리 VER 2.3.md   (3주차 최신)
```

### 파일별 한 줄 설명

- `GUNGON_Service_Planning_VER_2.1.md` — **현재 최신 서비스 기획.** VER 2.0 대비: 대표 프로그램 축소 섹션 추가, 경험 단계 명칭을 「준비 · 시선 · 체험 · 기억」으로 정리(2.0의 "해석/기록·확장" 대체), 8장을 "터치포인트 기준 + 경험 단계 기준" 두 축 정리로 교체, 용어를 영문 혼용에서 한글 표기(스마트 글라스/인터랙티브 스크린/웹)로 통일.
- `GUNGON_Service_Planning_VER 2.0.md` — 터치포인트 구조에 경험 단계 기준을 처음 추가한 버전. VER 2.1의 직전 단계.
- `GUNGON_Service_Planning_VER 1.0.md` — 서비스 목적/정책/역할/경험 정의(최초 통합본).
- `GUNGON_IA_VER 1.0.md` — 실제 정보/기능/상태/구조. Web=GUIDE·STATUS·RECORD, Smart Glass=PERSONA·EVENT·FOCUS, Interactive Screen=ACTION·FEEDBACK·RESULT.
- `GUNGON_Branding_VER 1.0.md` — STEP01~06 전체 요약 + STEP07(Visual Identity)·STEP08(Application) 후속작업 표시.
- `GUNG-ON_굿즈_섹션_정리_ver 1.0.md` — Figma `WngH1Jt8rwnA6HxQ99mMvv` 섹션 `굿즈`(node `2337:1533`)를 정리한 노트. **주의**: 이 섹션은 Figma "변경 로그" 페이지에 항목이 없는 별도 실험 영역으로, 현재 트래킹되는 17장 본 덱과 무관. 내용이 GPS(수집 정보)·NFC(굿즈 태그·리마인드)를 전제로 설계돼 있는데, GPS는 위 "사용하지 않는 기능" 목록에 명시적으로 금지돼 있고 NFC는 "핵심 기능으로 확정하지 않음" 상태라 본 덱 정책과 충돌함 — 이 굿즈 안을 정식 반영할지는 사용자 확인 필요(미해결 사항에도 기록).
- `01_STEP/01_…STEP1.md` ~ `05_…STEP5.md` — STEP01~05 상세본, 개별 파일.
- `06_research/Brand Moodboard Reference.md` — 무드보드 레퍼런스 원본.
- `07_raw/3주차/…` — 3주차 작업 원본. 정제된 결론은 `02_Service_Design`(VER 2.x)과 `04_Branding`으로 올라가고, 여기는 근거 원본으로 남긴다.

### 파일명 리네임 이력 (참고용)
- `GUNGON_Branding_Master.md`(Claude 최초 생성) → 사용자가 `GUNGON_Branding_VER 1.0.md`로 리네임
- `GUNGON_Service_Planning_Master.md` → `GUNGON_Service_Planning_VER 1.0.md`
- `GUNGON_IA_Master.md` → `GUNGON_IA_VER 1.0.md`
- `05_research/` → `06_research/` (2026-09-08~12 사이, 05 번호 중복 해소)
- Branding STEP 파일 방식은 다섯 번 바뀜: 개별파일 → 통합 → 번호 접두사 개별파일 → 통합 → **다시 개별파일로 `01_STEP/` 하위 배치(현재 최종)**.

### 아직 정리 안 된 위치
- `01_figma_make_ppt/figma_make_ppt_design_system_final.md`는 아직 `MJC/` 루트에 있음. **PPT 덱 자체**의 무채색 편집 스타일 규칙 문서(GUNG:ON 제품 컬러 시스템과는 별개).

# 연결된 외부 리소스

- **Figma 기본 작업 파일**: `GUNG:ON Figma ppt 제작` — https://www.figma.com/design/WngH1Jt8rwnA6HxQ99mMvv/GUNG-ON-Figma-ppt-%EC%A0%9C%EC%9E%91 (사용안내/변경 로그 페이지 포함)
- **Figma 원본/분석 파일**: `GUNG:ON Figma` — https://www.figma.com/design/ci38eNYyZHY0K5e1cAdYqw/%EC%A0%9C%EB%AA%A9-%EC%97%86%EC%9D%8C
- **공개 GitHub 미러**: https://github.com/shinhayoung02-cmd/gungon-figma-guide — 이 vault(`01_system`~`07_raw`) 전체를 그대로 미러링함. **이 vault를 수정할 때마다 그 즉시 이 레포에도 반영하고 커밋/푸시한다** (2026-09-06 사용자가 지속 동기화로 확정, Figma 파일간 반영과 달리 이건 매번 자동으로 한다).

# 우선순위 원칙

1. 사용자가 직접 준 지시
2. 이 인덱스 및 02_Service_Design/03_IA/04_Branding의 기획 원본
3. Figma 파일에서 실제 관찰한 스타일/구조 (레이아웃 템플릿, 디자인 토큰 등은 여기서 나온 것)

# 미해결 / 확인 필요 사항

- `GUNG-ON_굿즈_섹션_정리_ver 1.0.md`(굿즈 섹션, node `2337:1533`)가 GPS·NFC를 전제로 함 — "사용하지 않는 기능"(GPS 금지)·Custom Goods 정의(NFC 미확정)와 충돌. 이 굿즈 기획을 정식 반영할지, 아니면 그대로 실험안으로 둘지 확인 필요.
- `01_figma_make_ppt` 폴더를 `GUNG ON/` 안으로 옮길지 여부
- `05_Presentation` 폴더가 계속 비어 있음 — 발표자료를 여기 둘지, Figma만 쓸지 확인 필요
- `GUNGON_Service_Planning_VER_2.1.md` — 파일명이 `VER_2.1`(언더스코어)로 컨벤션(`VER 2.1`, 공백)과 다르고, 문서 안 제목은 아직 "(VER 2.0)"으로 남아 있음 — 확인 후 정정 필요
- `02_Service_Design`에 VER 1.0 / 2.0 / 2.1 세 버전 공존 — RULE 3의 "옛 버전은 `_archive_{날짜}/`로 이동" 적용할지 확인 필요
