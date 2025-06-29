# 📝 투두두두 - 살아 숨 쉬는 스케줄러

<img src="https://github.com/user-attachments/assets/1c111391-fd80-475f-94a7-ea8f0c95a5f5" alt="홈 화면" width="300"/>



**지루한 할 일 관리를, 살아 움직이는 몬스터와 함께!** <br>
투두두두는 애니메이션과 레벨 시스템이 결합된 게이미피케이션 기반 할 일 관리 앱입니다.

---

## ✏️ 프로젝트 개요

**투두두두**는 사용자가 입력한 할 일을 *몬스터 형태의 캐릭터*로 시각화하고,  
완료 시에는 애니메이션을 통해 몬스터를 처치하며 성취감을 주는 스케줄러 앱입니다.  
반복되는 일상을 재미있는 퀘스트처럼 즐기고, 성장하는 나를 시각적으로 확인할 수 있습니다.

**핵심 컨셉 요약:**
- 할 일 → 몬스터
- 완료 → 몬스터 처치 애니메이션
- 사용자 → 성장하는 캐릭터
- 직접 만든 그림도 움직이는 캐릭터로!

---

## 🔧 기술 스택

| 항목 | 사용 기술 |
|------|------------|
| **프론트엔드** | Android (Kotlin) |
| **백엔드** | Flask (Python) |
| **애니메이션 엔진** | Meta의 AnimatedDrawings 오픈소스 |
| **데이터베이스** | Android room db |
| **서버 배포 도구** | AWS EC2 |
| **협업 도구** | GitHub, Figma, Notion |

---

## 🧑‍🤝‍🧑 팀원 소개

| 이름 | 역할 | 주요 담당 |
|------|------|-----------|
| **권용빈** | PM & 디자인 | 서비스 구조 설계, UI/UX 디자인, 각종 문서 담당 |
| **김재경** | 백엔드+서버 | 애니메이션 생성 서버 개발, API 구현 |
| **이우신** | 프론트+서버 | 안드로이드 UI 개발, API 구현 및 앱 내 상호작용 구현 |
| **이우진** | 프론트 | 안드로이드 UI 개발, 앱 주요 기능 구현 |

---

## 🧩 주요 기능

- 할 일 등록 및 완료 기능
- 몬스터 캐릭터와 연결된 애니메이션 연출
- 경험치 및 레벨업 시스템
- 사용자 그림 업로드 → 나만의 캐릭터 생성 (AnimatedDrawings 활용)
- 퀘스트(할 일) 완료 시 성취감 있는 피드백 제공

---

## 🧪 앱 사용 튜토리얼

투두두두 앱의 주요 기능과 사용 흐름을 간략하게 안내합니다.

### 1. 앱 진입 및 스플래시 화면

- 앱 실행 시 로딩 및 로고 화면이 표시됩니다.

### 2. 퀘스트 등록 및 완료 처리

- 사용자가 등록한 할 일은 몬스터 형태로 시각화됩니다.
- 몬스터를 클릭하여 완료하면, 몬스터 처치 애니메이션과 함께 경험치가 쌓입니다.

### 3. 할 일 확인 및 날짜 관리

- 날짜를 선택하면 해당 날짜의 할 일을 확인하고, 우선순위 및 색상별로 구분된 할 일을 생성할 수 있습니다.

### 4. 나만의 캐릭터 만들기

- 사용자 이미지 또는 그림을 업로드하여 나만의 애니메이션 캐릭터를 생성할 수 있습니다.
- 생성된 캐릭터는 언제든 수정 및 편집이 가능합니다.


📖 더욱 자세한 앱 사용법과 기능 설명은  
[GitHub Wiki](https://github.com/OSSW-HideInBash/.github/wiki)에서 확인할 수 있습니다.

---
## 📁 주요 레포지토리

| 이름 | 설명 |
|------|------|
| [Android](https://github.com/OSSW-HideInBash/Android) | 안드로이드 앱 클라이언트 |
| [flask_server](https://github.com/OSSW-HideInBash/flask_server) | 백엔드 서버 및 애니메이션 연동 API |
| [AnimatedDrawings_ec2](https://github.com/OSSW-HideInBash/AnimatedDrawings_ec2) | Meta의 오픈소스를 기반으로 한 캐릭터 애니메이션 서버 |

---

## 📈 향후 계획 (확장 기능)

- 칭호 및 업적 시스템 (예: "30일 연속 달성")
- 캐릭터/몬스터 커스터마이징 (장비, 모션 등)
- 소셜 기능 (친구와 퀘스트 공유 및 응원)

---

## 🤝 Contributing Guide

이 프로젝트에 기여하고 싶다면 언제든지 환영합니다!

1. 이슈를 통해 버그, 기능 제안, 아이디어를 자유롭게 남겨주세요.
2. 기능 추가나 수정은 `dev` 브랜치를 기반으로 `feature/*` 또는 `fix/*` 브랜치를 생성해주세요.
3. [CONTRIBUTING.md](https://github.com/OSSW-HideInBash/.github/blob/main/CONTRIBUTING.md)를 참고하여 코드 스타일 및 커밋 메시지 규칙을 지켜주세요.
4. PR(Pull Request)은 **`dev` 브랜치로** 생성하고, 자세한 설명을 포함해주세요.

> 🔗 자세한 기여 가이드는 [CONTRIBUTING.md 전체 보기](https://github.com/OSSW-HideInBash/.github/blob/main/CONTRIBUTING.md)

---

## 🙏 Special Thanks

- [Meta AI - AnimatedDrawings](https://github.com/facebookresearch/AnimatedDrawings)  
  본 프로젝트의 애니메이션은 Meta AI의 오픈소스를 기반으로 구현되었습니다.

---
### Contributors
-kyb5272 (권용빈) https://github.com/kyb5272

-riadan710(이우진) https://github.com/riadan710

-davidjk522(김재경) https://github.com/davidjk522

-wslee670(이우신) https://github.com/wslee6704


**Team OSSW-HideInBash**
