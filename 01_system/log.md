# GUNG:ON Change Log

## 2026-09-07

---

# CHANGE 24 (Figma 프로덕션 규칙)
## 대제목(H1) 폰트 크기 규칙 확정 — 레이아웃 템플릿별로 분리(1번 56px / 2번 44px)

Figma 기본 작업 파일(`WngH1Jt8rwnA6HxQ99mMvv`)에서 "01 시스템 기획" 재구성 슬라이드 5장(node 68:2~74:2)의 대제목이 36px로 잘못 들어가 있던 걸 사용자가 지적해서 56px로 수정함. 이 김에 대제목 크기 규칙을 레이아웃 템플릿별로 분리 확정:

- 1번 레이아웃(좌측텍스트+우측/하단모듈형) — 대제목 56px ExtraBold
- 2번 레이아웃(상단전체폭타이틀+하단카드/스텝형) — 대제목 44px ExtraBold
- (예전엔 두 유형 모두 54px로 통일했었음 — 이 기준은 폐기)
- 부제/본문은 그대로 20px Medium #595959 유지

**적용 범위 — 사용자가 명시적으로 한정함**: 이 크기 규칙은 앞으로 새로 만드는 슬라이드에만 적용한다. 사용자가 이미 만든 기존 슬라이드의 폰트 크기는 이 규칙으로 되돌리거나 손대지 않는다.

같은 세션에서 실측 기반 "디자인 시스템" 페이지(Figma 신규 페이지, 변경 로그 다음 순서)도 추가함 — 실제 컬러 스와치, 폰트/헤더/카드 실물 샘플, 구분선 실측 색상(#E5E5E5, 예전 문서의 #D9DCE0는 오기) 등 실측 기반 정정 포함. 자세한 내용은 Figma "변경 로그" 페이지·"사용안내" ⑦-v4 참고.

---

## 2026-09-06

---

# CHANGE 12 (문서 구조)
## 폴더명 정리 + 신규 폴더 추가

- `02_기획` → `02_Service_Design`으로 이름 변경
- `04_브랜딩` → `04_Branding`으로 이름 변경
- `03_IA`는 이름 유지
- `05_Presentation`, `05_research` 폴더 신규 생성(현재 비어있음)
- 참고: `05_Presentation`과 `05_research`가 번호가 같음(05) — 의도한 구성인지 확인 필요

---

# CHANGE 23 (외부 연동)
## 이 vault를 공개 GitHub 레포에 미러링 + 지속 동기화 확정

`https://github.com/shinhayoung02-cmd/gungon-figma-guide`가 예전엔 Figma 요약 README 하나뿐이었는데, 이제 **이 vault 전체(01_system~05_research)를 그대로 미러링**하는 걸로 바뀜. 사용자가 "이 vault를 수정할 때마다 git에도 계속 동기화해달라"고 명시적으로 요청 — Figma 파일간 반영(요청할 때만 온디맨드)과 달리, **이건 vault를 건드릴 때마다 매번 자동으로 반영하고 커밋/푸시한다.**

- 로컬 레포 경로: `C:\Users\Admin\Documents\gungon-figma-guide`
- 루트 `README.md` = 이 `index.md`와 동일한 내용(GitHub 랜딩 페이지용)

---

# CHANGE 22 (문서 구조)
## 제목에 버전 표기 누락된 파일 전부 보완

다음 5개 파일 제목에 "(VER 1.0)"이 빠져 있어서 추가함(파일명에는 버전이 있었지만 문서 안 제목 줄에는 없었음):
- `GUNGON_Service_Planning_VER 1.0.md`
- `GUNGON_IA_VER 1.0.md`
- `GUNGON_Branding_VER 1.0.md`
- `00_Index/페르소나체험형_경복궁관람시스템_브랜딩_가이드_v1_0.md`
- `05_research/Brand Moodboard Reference.md`

`01_STEP/`의 STEP1~5 파일은 이미 제목에 표기돼 있어 그대로 둠. `01_system`(index/log/RULE)은 버전 표기 대상 아님(RULE.md 참고).

---

# CHANGE 21 (문서 구조)
## Branding STEP 파일, 통합 파일에서 다시 개별 파일로 (최종)

`01_STEP/STEP_VER 1.0.md`(통합본)를 삭제하고, STEP1~5를 다시 개별 파일로 분리해 `04_Branding/01_STEP/` 안에 넣음: `01_GUNGON_Brand_Strategy_STEP1.md`, `02_GUNGON_Naming_Verbal_STEP2.md`, `03_GUNGON_Reference_DesignMethod_STEP3.md`, `04_GUNGON_Brand_Moodboard_STEP4.md`, `05_GUNGON_Color_Origin_STEP5.md`. 내용은 손실 없이 그대로. STEP06(Color System)은 사용자가 "확정되면 나중에 줄게"라고 해서 아직 미작성.

---

# CHANGE 20 (문서 구조)
## STEP_VER 1.0.md를 새 하위폴더 01_STEP으로 이동

사용자가 `04_Branding` 안에 `01_STEP` 폴더를 직접 만들어둠(외부 변경). 그 안이 비어있어서 파일이 사라진 것으로 오해했으나, `STEP_VER 1.0.md`는 `04_Branding` 바로 밑에 그대로 있었음(내용 손실 없음, 27740바이트 그대로). `04_Branding/01_STEP/STEP_VER 1.0.md`로 이동 완료.

---

# CHANGE 19 (문서 구조)
## 무드보드 레퍼런스 파일을 05_research로 이동

`04_Branding/01_리서치/Brand Moodboard Reference.md` → `05_research/Brand Moodboard Reference.md`로 이동. 빈 `01_리서치` 폴더는 삭제. index.md 즉시 반영(RULE.md 규칙 적용 첫 사례).

---

# CHANGE 18 (문서 구조)
## RULE.md 신규 생성 + index.md를 실제 파일 전수 목록으로 개편 + Branding STEP 파일 재통합

1. `01_system/RULE.md` 신규 생성 — vault 운영 규칙(목적/폴더구조/작성원칙/파일명·링크 규칙/index 갱신 규칙/외부 변경 감지) 정리.
2. `01_system/index.md`를 큐레이션된 요약이 아니라 **실제 파일 트리 전수 목록**으로 개편(파일 트리 다이어그램 + 파일별 한줄설명 + 리네임 이력). 이 과정에서 그동안 놓쳤던 외부(Obsidian) 리네임 2건을 추가로 발견: `GUNGON_Service_Planning_Master.md` → `GUNGON_Service_Planning_VER 1.0.md`, `GUNGON_IA_Master.md` → `GUNGON_IA_VER 1.0.md`. index.md의 해당 파일명도 전부 수정.
3. **Branding STEP 파일을 다시 통합**: `01_GUNGON_Brand_Strategy_STEP1.md` ~ `05_GUNGON_Color_Origin_STEP5.md` 5개 개별 파일을 삭제하고, `STEP_VER 1.0.md` 한 파일로 재통합(내용 전부 보존, 섹션 제목에 STEP별 "(VER 1.0)" 표기 유지). 앞으로 이 vault를 만질 때마다 **index.md와 log.md를 그 즉시 함께 갱신**하는 것을 규칙(RULE.md)으로 명문화함.

---

# CHANGE 17 (문서 구조)
## Branding STEP 파일 최종 구조 확정 — 번호 접두사 개별 파일

`STEP_VER 1.md`(통합 파일)를 다시 폐기하고, STEP마다 번호 접두사가 붙은 개별 파일로 최종 확정:
- `01_GUNGON_Brand_Strategy_STEP1.md` (24섹션)
- `02_GUNGON_Naming_Verbal_STEP2.md` (40섹션)
- `03_GUNGON_Reference_DesignMethod_STEP3.md` (19섹션, ZARA 이무기 레퍼런스 + Design Method 상세)
- `04_GUNGON_Brand_Moodboard_STEP4.md` (34섹션, Architecture/Form/Material/Color/Mood 5축)
- `05_GUNGON_Color_Origin_STEP5.md` (36섹션, 오방색→8 Base Color 유래 상세)

전부 사용자가 직접 작성한 상세 확장판이고, 제목 옆에 "(VER 1.0)" 버전 표기를 추가함(요청사항). `GUNGON_Branding_VER 1.0.md`(전체 요약 Master)는 그대로 유지 — 개별 STEP 파일은 각 STEP의 상세본, Master는 전체 요약본 역할로 공존.

---

# CHANGE 16 (문서 구조)
## Branding STEP 파일을 개별 파일 → 통합 파일(STEP_VER 1)로 변경

사용자가 방침을 바꿔서, STEP별로 파일을 따로 만드는 대신 **`STEP_VER 1.md` 한 파일에 STEP_1, STEP_2 내용을 모두 넣는 방식**으로 전환. 기존 `STEP_1.md`, `STEP_2.md`는 삭제하고 `STEP_VER 1.md`로 통합(제목 옆에 버전 "VER 1" 표기). STEP_1 = Brand Strategy(24섹션), STEP_2 = Naming & Verbal Identity(40섹션), 둘 다 사용자가 직접 작성한 확장판.

**참고(외부 변경 발견)**: `GUNGON_Branding_Master.md`(Claude가 만든 파일명)가 이 작업 도중 확인해보니 `GUNGON_Branding_VER 1.0.md`로 바뀌어 있었음 — 로그에 기록 없이 사용자가 Obsidian에서 직접 리네임한 것으로 보임(용량/내용 동일, 이름만 다름). "Master"류 파일도 "VER X.0" 버전 네이밍으로 가는 게 사용자의 최신 컨벤션인 것으로 보임 — 앞으로 새 Master/통합 문서 만들 때 이 네이밍(VER 1.0 등) 반영 고려.

---

# CHANGE 15 (문서 구조)
## Branding STEP별 개별 파일 생성 시작 (→ CHANGE 16에서 통합 파일로 전환됨)

`04_Branding/STEP_1.md`(Brand Strategy, 사용자가 직접 작성한 확장판, 24개 섹션), `STEP_2.md`(Naming & Verbal Identity, 사용자 확장판, 40개 섹션) 생성 완료. `STEP_3.md`(Reference & Design Method), `STEP_4.md`(Brand Moodboard)는 사용자가 이어서 내용을 줄 예정이라 아직 미생성.

---

# CHANGE 14 (문서 구조)
## 04_Branding 문서를 Branding Master로 교체

`GUNGON_Branding_Master.md` 신규 생성(20개 섹션, STEP01~06 확정 + STEP07~08 후속작업 표시). 기존 3개 문서를 대체하고 완전히 삭제함(보관본 없음):
- `페르소나체험형_경복궁관람시스템_Brand_Strategy_STEP1.md`
- `궁온_Branding_STEP2_Naming_Verbal.md`
- `GUNGON_Color_System_Obangsaek.md`

`00_Index`의 브랜딩 가이드(v1_0)와 `01_리서치`의 무드보드 레퍼런스는 Master가 다루지 않는 후속 STEP/원본 자료라 그대로 유지.

STONE/WOOD 재질 모티브 건 **최종 확정**: 대표 Material Motif는 WOOD, STONE은 대표 모티브에서 제외/축소하지만 Color System의 Neutral 토큰 `STONE #6E6B61`은 유지(재질 모티브와 컬러 토큰은 별개 개념) — Figma 색상 슬라이드(S22/S23)의 8 Base Color 팔레트는 변경 불필요.

---

# CHANGE 13 (문서 구조)
## 브랜딩 체크리스트 파일명 변경

`04_Branding/00_Index/페르소나체험형_경복궁관람시스템_브랜딩_필요항목_전체정리.md` → `페르소나체험형_경복궁관람시스템_브랜딩_가이드_v1_0.md`로 이름 변경.

---

# CHANGE 11 (문서 구조)
## 02_기획, 03_IA 문서를 Master 체계로 완전 교체

기존 `02_기획`의 두 문서(서비스디자인 UX기획 v2.6, 보강안 3_4_5)와 `03_IA`의 IA 정보구조도 v1.5를, 사용자가 직접 작성한 **두 개의 Master 문서**로 전부 교체함:

- `02_기획/GUNGON_Service_Planning_Master.md` — 서비스 목적/정책/역할/경험 정의 (52개 섹션)
- `03_IA/GUNGON_IA_Master.md` — 실제 정보/기능/상태/구조 정의 (59개 섹션, Web=GUIDE·STATUS·RECORD / Smart Glass=PERSONA·EVENT·FOCUS / Interactive Screen=ACTION·FEEDBACK·RESULT 축)

옛 문서 3개는 처음엔 각 폴더의 `_archive_2026-09-06/`으로 이동(보관)했다가, 사용자 요청으로 **전부 완전히 삭제**함(보관본 없음). 이 시점부터 `02_기획`/`03_IA`에는 위 두 Master 파일만 존재하며, "기존 문서와 Master 문서가 충돌하면 Master가 우선한다"는 원칙이 두 문서 모두에 명시돼 있음.

---

# CHANGE 01
## Web 역할 변경

### 이전

- Smart Glass 연결
- 연결 상태 확인
- GPS
- 지도
- 공간 탐색
- NFC Web 진입

### 최신

WEB = 안내 · 현황 · 기록

#### 이용 안내
- 서비스 안내
- 이용 방법
- 언어 / 접근성

#### 관람 현황
- 현재 선택된 페르소나
- 프로그램 진행 상태
- 프로그램 완료 상태

#### 관람 기록
- 완료 프로그램
- 프로그램 결과
- 나의 관람 기록

#### 선택형 확장
- Custom Goods Preview
- 선택 구매

### 수정 대상

- 서비스디자인 문서의 Web 역할
- Web IA
- 전체 User Flow
- 운영 시나리오
- Touchpoint Responsibility
- 발표자료 Web 관련 장표

### 반드시 삭제

- Web ↔ Smart Glass 연결
- Smart Glass 연결 상태
- GPS / Map
- AI 동선
- NFC Web 진입

---

# CHANGE 02
## Smart Glass 정보 구조 변경

### 이전

- 페르소나 기반 콘텐츠
- 맞춤형 인터페이스

두 항목 모두 Persona 개인화를 설명해 역할이 중복됨.

### 최신

Smart Glass의 핵심 정보 축을 분리한다.

#### 01 Persona-based Interpretation

기준:
누구의 시선으로 볼 것인가

Flow:

페르소나 선택
→ 공간 인지
→ 페르소나-공간 관계
→ 페르소나별 해석

#### 02 Historical Event

기준:
이 공간에서 무슨 일이 있었는가

Flow:

현재 전각 인지
→ 대표 역사 사건 확인
→ 역사 장면
→ 핵심 맥락

#### 03 Focus Point

기준:
무엇을 주목해서 볼 것인가

- 핵심 오브젝트
- 공간의 주요 지점
- 선택적 상세 정보

### 수정 대상

- Smart Glass IA
- Smart Glass Functional Structure
- Smart Glass User Flow
- AI 역할 정의
- 발표자료 Smart Glass 장표

---

# CHANGE 03
## AI 역할 명확화

### 이전

AI가 역사 콘텐츠를 실시간 생성하는 것처럼 표현될 가능성이 있었음.

### 최신

AI는 역사적 사실 자체를 임의 생성하지 않는다.

전문가 검수 콘텐츠를 기반으로

- Persona에 맞는 정보 선택
- 현재 공간에 맞는 사건 선택
- 콘텐츠 구성
- 표현 방식 조정
- 정보 우선순위 조정

을 담당한다.

### 수정 대상

- AI 기능 설명
- Smart Glass 기획
- 서비스디자인 문서
- 발표자료 AI 관련 문구

---

# CHANGE 04
## Custom Goods 구조 변경

### 삭제

체험
→ 엽전 / Stamp
→ 수집
→ 무료 굿즈

### 최신

체험
→ 결과 저장
→ Web 관람 기록
→ Custom Goods Preview
→ 선택 구매
→ 일상에서 경험 리마인드

### 원칙

- 무료 보상 아님
- 구매 선택 사항
- Persona + Program Result 기반 개인화
- NFC는 현재 핵심 기능으로 확정하지 않음

### 수정 대상

- 서비스 Flow
- Web IA
- Goods IA
- After Experience
- 발표자료 Custom Goods 관련 내용

---

# CHANGE 05
## Interactive Screen

### 현재 유지

대표 프로그램은 2개.

1. 오늘의 수라상
2. 훈민정음 서재

### 역할

행동 · 체험

### 주요 Action

- 선택
- 조작
- 쓰기
- 배치
- 피드백
- 결과

### 주의

Estimated Time은 Program Intro에 넣지 않는다.

---

# CHANGE 06
## 전체 User Flow

### 최신

경복궁 방문
→ Web에서 서비스 확인
→ Smart Glass 대여
→ Smart Glass 착용
→ 왕 / 왕비 / 세자 선택
→ 실제 경복궁 관람
→ Persona 기반 해석
→ Historical Event
→ Focus Point
→ Program 도착
→ Interactive Screen 체험
→ 결과 저장
→ Web 관람 기록 확인
→ 다음 관람
→ Smart Glass 반납
→ [선택] Custom Goods 구매
→ 일상에서 경험 리마인드

### 수정 대상

- Service Flow
- Customer Journey
- IA Cross-Touchpoint Flow
- 운영 시나리오
- 발표자료 전체 경험 흐름

---

# CHANGE 07
## Smart Glass Persona

### 유지

- 왕
- 왕비
- 세자

### 삭제 / 금지

- 궁녀
- 신하
- 기타 Persona
- 3인칭 시점
- 1인칭 / 3인칭 Toggle

---

# CHANGE 08
## 실제 경복궁의 위치

경복궁은 Touchpoint가 아니다.

### 정의

Experience Environment / Physical Context

디지털 서비스가 실제 궁을 대체하는 것이 아니라
실제 공간을 해석하고 행동하게 만드는 Experience Layer를 제공한다.

### 수정 대상

- Service Architecture
- Touchpoint Map
- Service Design Overview

---

# CHANGE 09
## 발표 구조 변경

서비스 IA 자체의 변경이 아니라 Presentation Structure 변경.

### 01 시스템 기획

메인 발표에서는 5장만 사용.

1. 문제 정의 + 프로젝트 방향
2. 선택과 집중 + 최종 구조
3. 터치포인트 역할 + 전체 경험 흐름
4. 핵심 현장 경험
5. 관람 전 · 중 · 후 연결

### 상세 내용

- 운영 시나리오
- 이해관계자 구조
- 상세 IA
- 오류 상태

등은 부록 또는 기획 문서에서 관리한다.

---

# CHANGE 10
## Branding / Material

서비스 IA 변경이 아니라 Branding 변경.

### 현재 방향

WOOD를 대표 재질 모티브로 유지.

STONE은 대표 재질 모티브에서 축소 또는 제거 검토.

### Color

오방색을 문화적 출발점으로 사용하되
경복궁의 단청 · 기와 · 목재 · 석재 · 한지와 결합해
현대적인 컬러 시스템으로 재해석한다.

오방색과 8 Base Color를 1:1 대응시키지 않는다.

---

# 부록 — 문서/연동 변경 (2026-09-06)

- 기획 문서(`02_기획`, `03_IA`, `04_브랜딩`)를 `MJC/` 루트에서 `MJC/GUNG ON/` 하위로 재구성함. `01_figma_make_ppt`는 아직 `MJC/` 루트에 남아있음(이동 여부 미정).
- Claude 세션이 이 vault를 GUNG:ON 프로젝트의 소스오브트루스로 인식하고 자체 메모리에 연동.
- `01_system/index.md`, `01_system/log.md` 신규 생성.
- Figma 쪽에는 별도로 "사용안내"·"변경 로그" 페이지가 있음(기본 작업 파일 `WngH1Jt8rwnA6HxQ99mMvv`) — 이 vault의 log와는 서로 참고만 하고 독립적으로 유지.
