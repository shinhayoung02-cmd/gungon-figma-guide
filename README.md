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

마지막 확인: 2026-09-06 (`find`로 직접 대조함)

```text
GUNG ON/
├─ 01_system/
│  ├─ index.md          ← 이 파일
│  ├─ log.md             변경 로그
│  └─ RULE.md            운영 규칙(목적/폴더구조/작성원칙/파일명·링크 규칙)
│
├─ 02_Service_Design/
│  └─ GUNGON_Service_Planning_VER 1.0.md   서비스 기획 (유일 문서)
│
├─ 03_IA/
│  └─ GUNGON_IA_VER 1.0.md                 정보구조도 (유일 문서)
│
├─ 04_Branding/
│  ├─ GUNGON_Branding_VER 1.0.md    전체 요약 Master
│  ├─ 01_STEP/
│  │  ├─ 01_GUNGON_Brand_Strategy_STEP1.md
│  │  ├─ 02_GUNGON_Naming_Verbal_STEP2.md
│  │  ├─ 03_GUNGON_Reference_DesignMethod_STEP3.md
│  │  ├─ 04_GUNGON_Brand_Moodboard_STEP4.md
│  │  └─ 05_GUNGON_Color_Origin_STEP5.md
│  │     (STEP06 Color System 상세본은 사용자가 내용 확정되면 추후 전달 예정 — 아직 없음)
│  └─ 00_Index/
│     └─ 페르소나체험형_경복궁관람시스템_브랜딩_가이드_v1_0.md   STEP1~12 체크리스트(Master 밖 후속 STEP 포함)
│
├─ 05_Presentation/   (비어있음)
└─ 05_research/       (05_Presentation과 번호 중복, 확인 필요)
   └─ Brand Moodboard Reference.md      무드보드 레퍼런스 원본 (04_Branding/01_리서치에서 이동됨, 그 폴더는 삭제)
```

### 파일별 한 줄 설명

- `GUNGON_Service_Planning_VER 1.0.md` — 서비스 목적/정책/역할/경험 정의. 옛 UX기획 v2.6·보강안 3_4_5를 대체(삭제됨).
- `GUNGON_IA_VER 1.0.md` — 실제 정보/기능/상태/구조. Web=GUIDE·STATUS·RECORD, Smart Glass=PERSONA·EVENT·FOCUS, Interactive Screen=ACTION·FEEDBACK·RESULT. 옛 IA v1.5를 대체(삭제됨).
- `GUNGON_Branding_VER 1.0.md` — STEP01~06 전체 요약 + STEP07(Visual Identity)·STEP08(Application) 후속작업 표시. 옛 Brand_Strategy_STEP1·Branding_STEP2_Naming_Verbal·GUNGON_Color_System_Obangsaek를 대체(삭제됨).
- `01_STEP/01_GUNGON_Brand_Strategy_STEP1.md` ~ `05_GUNGON_Color_Origin_STEP5.md` — STEP01~05 상세본, 개별 파일(2026-09-06 최종 확정: 한 파일 통합 방식을 사용자가 다시 되돌려 개별 파일로 확정함). STEP06(Color System)은 사용자가 "확정되면 나중에 줄게"라고 함 — 아직 없음, 받으면 `06_GUNGON_Color_System_STEP6.md`로 추가.
- `05_research/Brand Moodboard Reference.md` — 원래 `04_Branding/01_리서치/`에 있었는데 `05_research`로 이동함(그 하위폴더는 삭제).

### 파일명 리네임 이력 (참고용)
- `GUNGON_Branding_Master.md`(Claude 최초 생성) → 사용자가 `GUNGON_Branding_VER 1.0.md`로 리네임
- `GUNGON_Service_Planning_Master.md` → `GUNGON_Service_Planning_VER 1.0.md`
- `GUNGON_IA_Master.md` → `GUNGON_IA_VER 1.0.md`
- 세 파일 모두 "VER 1.0" 버전 표기로 통일됨 — 앞으로 새 Master급 문서는 이 컨벤션(`GUNGON_{도메인}_VER {N}.0.md`)을 따른다.
- Branding STEP 파일 방식은 다섯 번 바뀜: 개별파일(STEP_1/STEP_2) → 통합(STEP_VER 1.md, STEP1~2만) → 번호 접두사 개별파일(STEP1~5) → 통합(STEP_VER 1.0.md, STEP1~5 전부) → **다시 개별파일로, `01_STEP/` 하위폴더 안에 배치(현재 최종)**.

### 아직 정리 안 된 위치
- `01_figma_make_ppt/figma_make_ppt_design_system_final.md`는 아직 `MJC/` 루트에 있고 `GUNG ON/` 폴더 안으로 안 옮겨져 있음. **PPT 덱 자체**의 무채색 편집 스타일 규칙 문서(GUNG:ON 제품 컬러 시스템과는 별개).

---

# 연결된 외부 리소스

- **Figma 기본 작업 파일**: `GUNG:ON Figma ppt 제작` — https://www.figma.com/design/WngH1Jt8rwnA6HxQ99mMvv/GUNG-ON-Figma-ppt-%EC%A0%9C%EC%9E%91 (사용안내/변경 로그 페이지 포함)
- **Figma 원본/분석 파일**: `GUNG:ON Figma` — https://www.figma.com/design/ci38eNYyZHY0K5e1cAdYqw/%EC%A0%9C%EB%AA%A9-%EC%97%86%EC%9D%8C
- **공개 GitHub 미러**: https://github.com/shinhayoung02-cmd/gungon-figma-guide — 이 vault(`01_system`~`05_research`) 전체를 그대로 미러링함. **이 vault를 수정할 때마다 그 즉시 이 레포에도 반영하고 커밋/푸시한다** (2026-09-06 사용자가 지속 동기화로 확정, Figma 파일간 반영과 달리 이건 매번 자동으로 한다).

# 우선순위 원칙

1. 사용자가 직접 준 지시
2. 이 인덱스 및 02_Service_Design/03_IA/04_Branding의 기획 원본
3. Figma 파일에서 실제 관찰한 스타일/구조 (레이아웃 템플릿, 디자인 토큰 등은 여기서 나온 것)

# 미해결 / 확인 필요 사항

- `01_figma_make_ppt` 폴더를 `GUNG ON/` 안으로 옮길지 여부
- `05_Presentation`과 `05_research` 폴더 번호가 둘 다 05로 동일 — 의도한 구성인지 확인 필요
