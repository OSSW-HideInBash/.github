# 🛠️ Contributing to 투두두두 - OSSW-HideInBash

환영합니다! 👋  
이 저장소는 **할 일을 몬스터로 표현하는 게이미피케이션 기반 스케줄러 "투두두두"**의 개발을 위한 팀 프로젝트입니다.

---

## 📌 기여 가능 영역

- 📱 Android 앱 기능 및 UI 개선
- 🖥 Flask 서버 기능 추가 또는 수정
- 🧞 AnimatedDrawings 연동 개선
- 📘 문서화 / 번역 / 오류 수정

---

## 🧱 코드 스타일 & 커밋 메시지

- **Android**: Kotlin 코드 → [Kotlin 공식 스타일 가이드](https://developer.android.com/kotlin/style-guide)
- **Flask 서버**: PEP8 스타일
- **커밋 메시지 규칙 (Prefix 권장)**:
  - `Feat`: 새로운 기능
  - `Fix`: 버그 수정
  - `Docs`: 문서 작성/수정
  - `Refactor`: 리팩토링

예: `[Feat] 퀘스트 완료 시 애니메이션 연동 추가`

---

## 🌿 브랜치 전략

- `main`: 최종 안정 버전
- `dev`: 개발 브랜치 (PR 대상)
- 기능 브랜치 예: `feature/quest-ui`, `fix/animation-bug`

---

## 🔁 Git Flow 기여 방식

이 프로젝트는 [Git Flow](https://nvie.com/posts/a-successful-git-branching-model/) 전략을 기본으로 합니다.  
아래와 같은 흐름으로 기능을 개발하고 병합해주세요:

1. `main` 브랜치는 **배포용** 최종 안정 버전입니다. 직접 커밋하지 않습니다.
2. `dev` 브랜치는 **모든 개발 작업이 병합되는 중간 단계 브랜치**입니다.
3. 새로운 기능 또는 버그 수정은 `feature/기능명`, `fix/버그명` 형태의 브랜치를 **`dev`에서 분기**해 만듭니다.
4. 기능 개발이 완료되면, `dev` 브랜치로 Pull Request를 생성하여 병합을 요청합니다.
5. 충분한 리뷰 후, `dev` → `main`으로 병합되며 릴리즈 또는 배포가 진행됩니다.

### 📌 브랜치 이름 규칙 예시
| 목적 | 브랜치 이름 |
|------|-------------|
| 기능 추가 | `feature/quest-animation` |
| 버그 수정 | `fix/login-crash` |
| 리팩토링 | `refactor/ui-cleanup` |

---

## 📬 PR 제출 시 주의사항

- `dev` 브랜치 대상으로 PR 생성
- PR 제목과 설명은 명확하게 작성
- 관련 이슈 번호가 있다면 연결 (`Closes #번호`)
- 충돌 없는 상태로 제출

---

## 🙋 문의/피드백

- 이슈 탭에 자유롭게 질문이나 제안 남겨주세요!
