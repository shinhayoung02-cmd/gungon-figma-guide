# GUNG:ON IA MASTER (VER 1.0)
## 페르소나 체험형 경복궁 관람 시스템 정보구조도

> 최종 업데이트 기준: 2026-09-06
> 서비스명: **궁온 / GUNG:ON**
> 기준 문서: `GUNGON_Service_Planning_Master.md`

---

# 1. IA 목적

본 IA는 궁온의 핵심 터치포인트인

- WEB
- SMART GLASS
- INTERACTIVE SCREEN

의 정보와 기능을 역할별로 분리하고,

관람 전 → 관람 중 → 관람 후까지
사용자의 경험이 하나의 시스템으로 이어지도록 구성한다.

궁온의 핵심 IA 원칙은 다음과 같다.

> **One Touchpoint, One Role**

각 터치포인트가 동일한 기능을 반복하지 않고
자신의 핵심 역할만 담당하도록 한다.

---

# 2. 전체 시스템 IA

```text
GUNG:ON
│
├─ 01. WEB
│  │
│  ├─ 이용 안내
│  ├─ 관람 현황
│  ├─ 나의 관람 기록
│  └─ 선택형 Custom Goods
│
├─ 02. SMART GLASS
│  │
│  ├─ 시작 / Persona Select
│  ├─ 기본 관람
│  ├─ Persona-based Interpretation
│  ├─ Historical Event
│  ├─ Focus Point
│  └─ Program Arrival
│
└─ 03. INTERACTIVE SCREEN
   │
   ├─ 오늘의 수라상
   └─ 훈민정음 서재
```

---

# 3. Touchpoint Responsibility

## 01 WEB

### 역할

**안내 · 현황 · 기록**

웹은 사용자가 서비스를 이해하고,
현재 관람 상태를 확인하고,
관람 이후 자신의 경험을 다시 확인하는 역할을 담당한다.

---

## 02 SMART GLASS

### 역할

**선택 · 관람 · 해석**

스마트 글라스는
사용자가 실제 경복궁 공간을 바라보는 과정에서

- 누구의 시선으로 보는지
- 이 공간에서 어떤 일이 있었는지
- 무엇을 주목해야 하는지

를 해석하도록 돕는다.

---

## 03 INTERACTIVE SCREEN

### 역할

**행동 · 체험**

인터랙티브 스크린은
공간의 역사적 기능과 연결된 행동을
사용자가 직접 수행하도록 한다.

---

## OPTIONAL CUSTOM GOODS

### 역할

**개인화 · 선택 구매 · 리마인드**

커스텀 굿즈는 핵심 터치포인트가 아니라
관람 이후 선택적으로 이어지는 확장 요소다.

---

# 4. WEB IA

```text
WEB
│
├─ 01. 이용 안내
│  │
│  ├─ 서비스 안내
│  ├─ 이용 방법
│  └─ 언어 / 접근성
│
├─ 02. 관람 현황
│  │
│  ├─ 현재 선택된 페르소나
│  ├─ 프로그램 진행 상태
│  └─ 프로그램 완료 상태
│
├─ 03. 나의 관람 기록
│  │
│  ├─ 방문 정보
│  ├─ 완료한 프로그램
│  ├─ 프로그램별 체험 결과
│  └─ 관람 기록
│
└─ 04. Custom Goods [선택]
   │
   ├─ 개인화 결과 확인
   ├─ 굿즈 미리보기
   ├─ 상품 선택
   └─ 구매
```

---

# 5. WEB 상세 구조

## 5.1 이용 안내

```text
이용 안내
│
├─ 서비스 안내
│  ├─ GUNG:ON 소개
│  ├─ 서비스 목적
│  └─ 주요 경험 소개
│
├─ 이용 방법
│  ├─ Smart Glass 이용 안내
│  ├─ Interactive Screen 이용 안내
│  └─ 전체 관람 흐름 안내
│
└─ 언어 / 접근성
   ├─ 언어 선택
   └─ 접근성 관련 설정
```

### 역할

관람 전에 사용자가
서비스의 구조와 이용 방법을 이해하도록 한다.

---

# 6. WEB 관람 현황

```text
관람 현황
│
├─ 현재 선택된 페르소나
│  ├─ 왕
│  ├─ 왕비
│  └─ 세자
│
├─ 프로그램 진행 상태
│  ├─ 오늘의 수라상
│  └─ 훈민정음 서재
│
└─ 완료 상태
   ├─ 미참여
   ├─ 진행
   └─ 완료
```

### 원칙

Web에서는 페르소나를 선택하지 않는다.

선택된 페르소나는
Smart Glass에서 선택된 결과를 **확인만** 한다.

---

# 7. WEB 나의 관람 기록

```text
나의 관람 기록
│
├─ 방문 정보
│  └─ 방문 날짜
│
├─ 완료 프로그램
│  ├─ 오늘의 수라상
│  └─ 훈민정음 서재
│
├─ 프로그램 결과
│  ├─ 수라상 결과
│  └─ 훈민정음 결과
│
└─ 관람 기록
   ├─ 선택한 페르소나
   ├─ 완료 프로그램
   └─ 체험 결과
```

### 역할

관람 중 또는 관람 이후
사용자가 자신이 경험한 내용을 확인하도록 한다.

---

# 8. WEB Custom Goods

```text
Custom Goods
│
├─ 개인화 정보
│  ├─ 선택한 페르소나
│  ├─ 프로그램 결과
│  └─ 방문 정보
│
├─ 미리보기
│  ├─ 결과 적용
│  └─ 상품 Preview
│
├─ 상품 선택
│
└─ 구매
   ├─ 현장 수령
   └─ 배송
```

### 중요

Custom Goods는 무료 보상이 아니다.

```text
프로그램 완료
≠
무료 굿즈 획득
```

사용자가 원할 경우
자신의 체험 결과가 반영된 상품을 선택해 구매한다.

---

# 9. WEB에서 제외되는 기능

다음 기능은 현재 WEB IA에 포함하지 않는다.

- Smart Glass 연결
- Smart Glass 연결 상태
- Smart Glass 장비 제어
- GPS
- Map
- 현재 위치 지도
- 전각 Pin
- 지도 기반 탐색
- AI 동선 추천
- 페르소나 선택
- 역사 장면
- 상세 공간 해설
- Digital Stamp
- 실물 엽전
- NFC를 통한 Web 진입

---

# 10. SMART GLASS IA

```text
SMART GLASS
│
├─ L0. 시작
│  │
│  ├─ Persona Select
│  │  ├─ 왕
│  │  ├─ 왕비
│  │  └─ 세자
│  │
│  └─ Persona Brief
│
├─ L1. 기본 관람
│  │
│  ├─ 현재 전각
│  ├─ 최소 HUD
│  ├─ 방향 안내
│  └─ 안전 상태
│
├─ L2. Persona-based Interpretation
│  │
│  ├─ 현재 Persona
│  ├─ Persona ↔ 공간 관계
│  ├─ Persona별 공간 해석
│  └─ 관련 역사 콘텐츠
│
├─ L3. Historical Event
│  │
│  ├─ 현재 전각의 대표 사건
│  ├─ 사건 Trigger
│  ├─ 역사 장면
│  ├─ 당시 인물 / 행동
│  └─ 핵심 맥락
│
├─ L4. Focus Point
│  │
│  ├─ 주요 지점
│  ├─ 오브젝트 강조
│  ├─ 핵심 의미
│  └─ 선택 상세 정보
│
└─ L5. Program Arrival
   │
   ├─ 프로그램 도착 알림
   ├─ 프로그램 이름
   └─ 체험 진입 안내
```

---

# 11. SMART GLASS L0 — Persona Select

## 구조

```text
Smart Glass 착용
↓
Persona Select
│
├─ 왕
├─ 왕비
└─ 세자
↓
Persona Brief
↓
관람 시작
```

---

## Persona 선택 원칙

선택 가능한 인물은 3개로 제한한다.

### 왕

왕의 역할과 관계된 공간을 중심으로 해석

### 왕비

왕비의 생활과 관계된 공간을 중심으로 해석

### 세자

세자의 생활과 역할에 연결된 공간을 중심으로 해석

---

# 12. Persona Brief

페르소나 선택 직후
사용자가 자신의 관람 관점을 이해할 수 있도록
짧은 정보를 제공한다.

```text
Persona Brief
│
├─ 인물
├─ 역할
├─ 공간과의 관계
└─ 이번 관람에서 바라볼 관점
```

### 원칙

긴 역사 소개보다

> **"나는 누구이며, 어떤 시선으로 경복궁을 보게 되는가"**

를 이해하는 데 집중한다.

---

# 13. SMART GLASS L1 — 기본 관람

```text
기본 관람
│
├─ 현재 전각
├─ 최소 HUD
├─ 방향 안내
└─ 안전 상태
```

---

## 원칙

기본 상태에서는 실제 경복궁 공간이 가장 먼저 보여야 한다.

화면을 정보로 채우지 않는다.

### 기본 노출 정보

- 현재 공간 이름
- 최소한의 이동 안내
- 필요한 상태 정보

---

# 14. SMART GLASS L2 — Persona-based Interpretation

## 핵심 질문

> **누구의 시선으로 이 공간을 볼 것인가**

### 구조

```text
Persona-based Interpretation
│
├─ 현재 Persona
├─ 현재 공간
├─ Persona ↔ 공간 관계
└─ Persona별 해석
```

---

## Flow

```text
Persona 선택
↓
현재 공간 인지
↓
Persona와 공간의 관계 확인
↓
해당 Persona 관점의 콘텐츠 선택
↓
Persona별 공간 해석 제공
```

---

## 예시 개념

같은 전각이라도

```text
왕
→ 통치 / 업무 / 국가 운영 관점

왕비
→ 생활 / 궁중 역할 / 공간 관계 관점

세자
→ 교육 / 성장 / 왕위 계승 관점
```

처럼 정보의 초점이 달라질 수 있다.

---

# 15. SMART GLASS L3 — Historical Event

## 핵심 질문

> **이 공간에서 실제로 무슨 일이 있었는가**

페르소나 기반 해석과 구분되는
독립적인 공간 중심 콘텐츠다.

---

## 구조

```text
Historical Event
│
├─ 현재 전각
├─ 해당 공간의 대표 사건
├─ 사건 Trigger
├─ 역사 장면
├─ 당시 인물
├─ 당시 행동
└─ 사건 핵심 맥락
```

---

## Flow

```text
현재 전각 인지
↓
해당 공간과 연결된 역사 사건 확인
↓
대표 사건 선택
↓
역사 장면 제공
↓
핵심 맥락 확인
↓
기본 관람 복귀
```

---

## Persona와의 차이

```text
PERSONA
인물 중심

누구의 시선으로 볼 것인가
```

```text
HISTORICAL EVENT
공간 중심

이곳에서 무슨 일이 있었는가
```

Historical Event는
반드시 Persona 개인화 콘텐츠로 다시 설명하지 않는다.

---

# 16. Historical Event 콘텐츠 단위

각 사건 콘텐츠는 아래 정도의 단위로 구성한다.

```text
Historical Event
│
├─ 사건 이름
├─ 시점
├─ 장소
├─ 주요 인물
├─ 핵심 상황
├─ 역사 장면
└─ 짧은 설명
```

### 원칙

- 긴 연표식 설명 지양
- 사건 전체보다 핵심 장면 중심
- 현재 실제 공간과 연결
- 전문가 검수 기반

---

# 17. SMART GLASS L4 — Focus Point

## 핵심 질문

> **이 공간에서 무엇을 주목해서 봐야 하는가**

---

## 구조

```text
Focus Point
│
├─ 주요 공간 지점
├─ 주요 오브젝트
├─ 시각적 강조
├─ 핵심 의미
└─ 선택 상세 정보
```

---

## 사용 예

- 왕좌
- 건축 구조
- 문
- 창호
- 기둥
- 특정 공간 영역
- 역사적 의미가 있는 오브젝트

### 원칙

실제 공간을 가리지 않도록
필요할 때만 최소한으로 강조한다.

---

# 18. SMART GLASS L5 — Program Arrival

```text
Program Arrival
│
├─ 현재 프로그램 공간 도착
├─ 프로그램 이름
├─ 짧은 소개
└─ Interactive Screen 안내
```

---

## 목적

Smart Glass에서 프로그램 전체를 실행하지 않는다.

Smart Glass는

> **"여기에서 체험할 프로그램이 있다"**

는 사실을 알려주고
사용자를 Interactive Screen으로 자연스럽게 연결한다.

---

# 19. SMART GLASS 사용 상태

```text
SMART GLASS STATE
│
├─ Idle
│
├─ Persona Select
│
├─ Viewing
│
├─ Persona Interpretation
│
├─ Historical Event
│
├─ Focus Point
│
├─ Program Arrival
│
└─ Error / Safety
```

---

# 20. SMART GLASS 시점 원칙

스마트 글라스는 **1인칭 시점으로 고정**한다.

### 사용하지 않는 상태

- Third Person
- Character View
- 1st / 3rd Toggle
- Avatar 중심 화면

---

# 21. SMART GLASS AI 구조

AI는 역사 정보를 자유롭게 생성하지 않는다.

```text
Expert-reviewed Historical Content
↓
현재 공간
+
현재 Persona
↓
AI
│
├─ 콘텐츠 선택
├─ 우선순위 조정
├─ 표현 방식 구성
└─ 맥락 연결
↓
User
```

---

# 22. Persona-based AI

```text
INPUT

Persona
+
Current Space

↓

PROCESS

관련 콘텐츠 선택
정보 우선순위 조정
Persona 관점 구성

↓

OUTPUT

Persona-based Interpretation
```

---

# 23. Historical Event AI

```text
INPUT

Current Space

↓

PROCESS

검수된 역사 사건 탐색
대표 사건 선택
장면과 맥락 구성

↓

OUTPUT

Historical Event
```

### 주의

`역사적 사건 생성`이 아니라

> **검수된 사건의 선택 · 구성 · 제공**

으로 정의한다.

---

# 24. INTERACTIVE SCREEN IA

```text
INTERACTIVE SCREEN
│
├─ 01. 프로그램 진입
│  ├─ 프로그램 이름
│  ├─ 프로그램 소개
│  └─ 역사적 맥락
│
├─ 02. 오늘의 수라상
│  ├─ 음식 선택
│  ├─ 디지털 조리
│  ├─ 수라상 배치
│  ├─ 피드백
│  ├─ 결과
│  └─ 완료
│
└─ 03. 훈민정음 서재
   ├─ 문장 입력
   ├─ 변환
   ├─ 먹 갈기
   ├─ 붓글씨 쓰기
   ├─ 결과
   └─ 완료
```

---

# 25. Interactive Screen 공통 구조

```text
PROGRAM
│
├─ Intro
├─ Context
├─ Action
├─ Feedback
├─ Result
└─ Complete
```

---

# 26. 오늘의 수라상 IA

```text
오늘의 수라상
│
├─ P0. Intro
│  ├─ 프로그램 이름
│  └─ 짧은 소개
│
├─ P1. Context
│  └─ 왕실 수라 관련 역사 맥락
│
├─ P2. 음식 선택
│  ├─ 음식 목록
│  └─ 선택 상태
│
├─ P3. 디지털 조리
│  ├─ 조리 행동
│  └─ 조리 피드백
│
├─ P4. 수라상 배치
│  ├─ 음식 배치
│  └─ 상차림 완성
│
├─ P5. Result
│  ├─ 나의 수라상
│  └─ 결과 정보
│
└─ P6. Complete
   └─ 체험 완료
```

---

# 27. 훈민정음 서재 IA

```text
훈민정음 서재
│
├─ P0. Intro
│  ├─ 프로그램 이름
│  └─ 짧은 소개
│
├─ P1. Context
│  └─ 훈민정음 관련 역사 맥락
│
├─ P2. 문장 입력
│  └─ 사용자 입력
│
├─ P3. 변환
│  └─ 입력 결과 변환
│
├─ P4. 먹 갈기
│  ├─ 행동
│  └─ 피드백
│
├─ P5. 붓글씨 쓰기
│  ├─ 쓰기
│  └─ 피드백
│
├─ P6. Result
│  ├─ 완성 결과
│  └─ 결과 저장
│
└─ P7. Complete
   └─ 체험 완료
```

---

# 28. Program 참여 원칙

프로그램은 선택 사항이다.

```text
Program Arrival
↓
참여
OR
건너뛰기
```

모든 프로그램을 완료해야만
다음 관람으로 이동할 수 있는 구조를 사용하지 않는다.

---

# 29. Program Intro에서 제외되는 정보

프로그램 소개 화면에는
예상 소요시간을 필수 정보로 제공하지 않는다.

즉,

```text
Estimated Time
```

항목은 현재 IA에서 제외한다.

---

# 30. Program Result

프로그램의 결과는
관람 이후 다시 확인할 수 있도록 저장한다.

```text
Interactive Screen
Program Result
↓
Result Storage
↓
WEB
나의 관람 기록
```

---

# 31. Cross-Touchpoint Flow

```text
WEB
서비스 안내
↓
현장 방문
↓
SMART GLASS
Persona Select
↓
SMART GLASS
기본 관람
↓
Persona-based Interpretation
↓
Historical Event
↓
Focus Point
↓
Program Arrival
↓
INTERACTIVE SCREEN
Program
↓
Result
↓
WEB
관람 현황 / 관람 기록
↓
SMART GLASS
다음 공간 관람
```

---

# 32. 관람 종료 Flow

```text
Smart Glass 관람 종료
↓
Smart Glass 반납
↓
WEB
나의 관람 기록 확인
↓
[선택]
Custom Goods
↓
상품 미리보기
↓
구매
↓
일상에서 경험 리마인드
```

---

# 33. 전체 사용자 Journey IA

```text
BEFORE
│
└─ WEB
   ├─ 서비스 안내
   ├─ 이용 방법
   └─ 언어 / 접근성

↓

DURING
│
├─ SMART GLASS
│  ├─ Persona Select
│  ├─ Persona Interpretation
│  ├─ Historical Event
│  ├─ Focus Point
│  └─ Program Arrival
│
├─ INTERACTIVE SCREEN
│  ├─ 오늘의 수라상
│  └─ 훈민정음 서재
│
└─ WEB
   ├─ 관람 현황
   └─ 프로그램 상태

↓

AFTER
│
└─ WEB
   ├─ 나의 관람 기록
   ├─ 프로그램 결과
   └─ Custom Goods
```

---

# 34. IA 역할 중복 방지

## Persona 선택

### 사용

Smart Glass

### 사용하지 않음

Web
Interactive Screen

---

## 공간 해석

### 사용

Smart Glass

### 사용하지 않음

Web
Interactive Screen

---

## 역사적 사건 장면

### 사용

Smart Glass

### 사용하지 않음

Web의 핵심 기능
Interactive Screen의 핵심 기능

---

## 직접 행동

### 사용

Interactive Screen

### 사용하지 않음

Web
Smart Glass

---

## 관람 기록

### 사용

Web

### 사용하지 않음

Smart Glass의 핵심 역할
Interactive Screen의 핵심 역할

---

# 35. 데이터 연결 구조

터치포인트의 기능은 분리하지만
관람 결과 데이터는 서비스 내부에서 연결된다.

```text
USER SESSION
│
├─ Persona
│
├─ Visit
│
├─ Program Status
│
├─ Program Result
│
└─ Goods Personalization
```

---

# 36. Persona Data

```text
PERSONA
│
├─ Persona ID
├─ 왕 / 왕비 / 세자
├─ 선택 상태
└─ 해당 관람 Session
```

---

# 37. Visit Data

```text
VISIT
│
├─ Visit ID
├─ 방문 날짜
├─ Persona
├─ Program Status
└─ Program Result
```

---

# 38. Program Data

```text
PROGRAM
│
├─ 오늘의 수라상
│  ├─ 참여 상태
│  ├─ 선택 결과
│  └─ 최종 결과
│
└─ 훈민정음 서재
   ├─ 참여 상태
   ├─ 입력 결과
   └─ 최종 결과
```

---

# 39. Goods Personalization Data

```text
CUSTOM GOODS
│
├─ Persona
├─ Program Result
├─ Visit Date
└─ User Selected Option
```

현재 단계에서는 NFC 데이터를
필수 구조로 포함하지 않는다.

---

# 40. 상태 구조

## Program Status

```text
NOT STARTED
↓
IN PROGRESS
↓
COMPLETED
```

프로그램을 건너뛴 경우

```text
NOT PARTICIPATED
```

상태로 구분할 수 있다.

---

# 41. Smart Glass Error IA

```text
ERROR
│
├─ 공간 인식 실패
├─ Network Error
├─ Battery Low
├─ Content Load Error
└─ Safety Alert
```

### 원칙

오류가 발생하더라도
실제 경복궁 관람은 계속할 수 있어야 한다.

---

# 42. Interactive Screen Error IA

```text
ERROR
│
├─ Input Error
├─ Interaction Error
├─ Result Save Error
├─ Device Error
└─ User Exit
```

---

# 43. Web Error IA

```text
ERROR
│
├─ Network Error
├─ Status Load Error
├─ Result Load Error
└─ Purchase Error
```

---

# 44. Historical Content Structure

역사 콘텐츠는 아래와 같이 관리할 수 있다.

```text
HISTORICAL CONTENT
│
├─ Persona Content
│
├─ Space Content
│
├─ Historical Event
│
├─ Focus Point
│
└─ Program Context
```

---

# 45. Persona Content

```text
PERSONA CONTENT
│
├─ 왕
│
├─ 왕비
│
└─ 세자
   │
   └─ 공간별 해석
```

---

# 46. Space Content

```text
SPACE
│
├─ 전각 ID
├─ 전각 이름
├─ 공간 기능
├─ Persona Relation
├─ Historical Event
├─ Focus Point
└─ Program 여부
```

---

# 47. Historical Event Content

```text
HISTORICAL EVENT
│
├─ Event ID
├─ Event Name
├─ Space ID
├─ Time
├─ People
├─ Situation
├─ Scene Content
├─ Core Context
└─ Verification Status
```

---

# 48. Focus Point Content

```text
FOCUS POINT
│
├─ Focus ID
├─ Space ID
├─ Object / Location
├─ Label
├─ Short Description
└─ Optional Detail
```

---

# 49. Program Content

```text
PROGRAM
│
├─ Program ID
├─ Program Name
├─ Space
├─ Historical Context
├─ Interaction
├─ Result
└─ Result Storage
```

---

# 50. 역사 콘텐츠 검수 상태

각 역사 콘텐츠에는
검수 여부를 구분할 수 있는 상태가 필요하다.

```text
CONTENT STATUS
│
├─ Draft
├─ Review
├─ Verified
└─ Published
```

### 원칙

사용자에게 제공하는 콘텐츠는
`Verified` 이후의 콘텐츠를 기준으로 한다.

---

# 51. AI와 IA의 관계

AI는 새로운 최상위 메뉴가 아니다.

즉 IA에

```text
AI
├─ AI Persona
├─ AI Event
└─ AI Guide
```

처럼 별도 메뉴를 만들지 않는다.

AI는 각 기능 내부에서
콘텐츠를 연결하는 **System Logic**으로 작동한다.

---

# 52. IA에서 제외되는 이전 구조

아래 구조는 최신 IA에 포함하지 않는다.

```text
WEB
├─ Map
├─ GPS
├─ Smart Glass Connection
├─ Stamp
├─ Coin
└─ AI Route
```

---

# 53. Reward IA 삭제

이전 구조:

```text
Program
↓
Stamp
↓
Coin
↓
Reward
↓
Free Goods
```

삭제.

현재 구조:

```text
Program
↓
Result
↓
Record
↓
[Optional]
Custom Goods Purchase
```

---

# 54. Smart Glass 이전 구조 삭제

삭제:

```text
Persona
+
맞춤형 Interface
```

처럼 두 기능이 모두 Persona 개인화를 설명하는 구조.

현재:

```text
Persona-based Interpretation
+
Historical Event
+
Focus Point
```

으로 구분한다.

---

# 55. 최종 IA 핵심 축

## WEB

```text
GUIDE
STATUS
RECORD
```

---

## SMART GLASS

```text
PERSONA
EVENT
FOCUS
```

---

## INTERACTIVE SCREEN

```text
ACTION
FEEDBACK
RESULT
```

---

## CUSTOM GOODS

```text
PERSONALIZE
PREVIEW
PURCHASE
REMIND
```

---

# 56. 최종 IA Summary

```text
GUNG:ON
│
├─ WEB
│  │
│  ├─ GUIDE
│  │  ├─ 서비스 안내
│  │  ├─ 이용 방법
│  │  └─ 언어 / 접근성
│  │
│  ├─ STATUS
│  │  ├─ 현재 Persona
│  │  └─ Program Status
│  │
│  ├─ RECORD
│  │  ├─ Visit
│  │  ├─ Completed Program
│  │  └─ Program Result
│  │
│  └─ CUSTOM GOODS [OPTIONAL]
│     ├─ Personalization
│     ├─ Preview
│     └─ Purchase
│
├─ SMART GLASS
│  │
│  ├─ PERSONA SELECT
│  │  ├─ 왕
│  │  ├─ 왕비
│  │  └─ 세자
│  │
│  ├─ VIEWING
│  │  ├─ Current Space
│  │  └─ Minimal HUD
│  │
│  ├─ PERSONA INTERPRETATION
│  │  └─ Persona × Space
│  │
│  ├─ HISTORICAL EVENT
│  │  ├─ Representative Event
│  │  ├─ Historical Scene
│  │  └─ Core Context
│  │
│  ├─ FOCUS POINT
│  │  ├─ Object
│  │  └─ Meaning
│  │
│  └─ PROGRAM ARRIVAL
│     └─ Interactive Screen 안내
│
└─ INTERACTIVE SCREEN
   │
   ├─ 오늘의 수라상
   │  ├─ Intro
   │  ├─ Context
   │  ├─ Select
   │  ├─ Cook
   │  ├─ Arrange
   │  ├─ Result
   │  └─ Complete
   │
   └─ 훈민정음 서재
      ├─ Intro
      ├─ Context
      ├─ Input
      ├─ Transform
      ├─ Ink
      ├─ Write
      ├─ Result
      └─ Complete
```

---

# 57. IA 최종 원칙

1. Web은 안내 · 현황 · 기록을 담당한다.
2. Web에서 Persona를 선택하지 않는다.
3. Web과 Smart Glass를 사용자가 직접 연결하지 않는다.
4. Smart Glass에서 Persona를 선택한다.
5. Smart Glass는 1인칭 시점만 사용한다.
6. Persona는 왕 / 왕비 / 세자로 제한한다.
7. Persona-based Interpretation과 Historical Event를 구분한다.
8. Historical Event는 공간 중심 기능이다.
9. Focus Point는 실제 공간에서 무엇을 볼지 알려준다.
10. Interactive Screen은 행동 중심이다.
11. 프로그램은 오늘의 수라상과 훈민정음 서재 두 개만 사용한다.
12. 프로그램 참여는 선택 사항이다.
13. Program Intro에는 예상 소요시간을 필수로 넣지 않는다.
14. 결과 데이터는 Web의 관람 기록으로 연결한다.
15. Stamp와 Coin은 사용하지 않는다.
16. Custom Goods는 무료 보상이 아니라 선택 구매다.
17. NFC는 현재 필수 IA에 포함하지 않는다.
18. AI는 독립 메뉴가 아니라 콘텐츠 선택과 구성 로직이다.
19. 역사 콘텐츠는 검수된 정보를 기반으로 제공한다.
20. 실제 경복궁이 항상 경험의 중심이다.

---

# 58. Master Source Rule

앞으로 기존 IA 문서와 본 문서가 충돌할 경우
**본 `GUNGON_IA_Master.md`의 최신 구조를 우선한다.**

특히 아래 이전 기능은 다시 추가하지 않는다.

- Web ↔ Smart Glass Connection
- GPS
- Map
- AI Route
- Stamp
- Coin
- Free Goods
- Third Person Smart Glass
- Persona 중복 개인화 기능

Smart Glass의 핵심 IA는 반드시 아래 구조를 유지한다.

```text
Persona Select

↓

Persona-based Interpretation
누구의 시선인가

+

Historical Event
이 공간에서 무슨 일이 있었는가

+

Focus Point
무엇을 주목해야 하는가

↓

Program Arrival
```

---

# 59. 기획 Master와 IA Master 관계

```text
GUNGON_Service_Planning_Master.md
서비스의 목적 / 정책 / 역할 / 경험 정의

↓

GUNGON_IA_Master.md
실제 정보 / 기능 / 상태 / 구조 정의

↓

화면 설계
Web
Smart Glass
Interactive Screen

↓

Prototype
```

두 Master 문서는 같은 최신 기획 기준을 사용한다.
