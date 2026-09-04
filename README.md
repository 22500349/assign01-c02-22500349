# My Profile Page

AI를 활용해 자기소개 웹페이지를 만들고, Git/GitHub 버전 관리와 Vercel 배포까지 실습한 프로젝트입니다.

## 프로젝트 설명

- `index.html` — AI를 활용하여 처음 생성한 자기소개 원본 페이지
- `index2.html` — 원본을 복사한 뒤 색상·글꼴·내용·요소를 직접 수정한 페이지
- 제작자: 선승범 (22500349, AI컴퓨터 전자 / 전산심화)

## Deploy URL

| 구분 | URL |
|---|---|
| Vercel Deploy | https://assign01-c02-22500349.vercel.app/ |
| index.html | https://assign01-c02-22500349.vercel.app/index.html |
| index2.html | https://assign01-c02-22500349.vercel.app/index2.html |

> 루트(`/`) 접속 시 `vercel.json` 설정으로 index2.html로 이동합니다.

---

## Weekly Review

### Key Learning — 이번 주 배운 핵심 3가지
1. **개발 환경 구성**: VS Code와 확장 프로그램, Git을 설치하고 로컬 프로젝트를 GitHub Repository와 연결하는 방법을 익혔습니다.
2. **버전 관리 흐름**: `add → commit → push`로 변경 이력을 남기고, GitHub Commit History로 작업 과정을 추적하는 법을 배웠습니다.
3. **자동 배포**: GitHub에 Push하면 Vercel이 변경 사항을 감지해 자동으로 재배포하는 CI 흐름을 경험했습니다.

### Development Flow
```
VS Code → HTML → Git → GitHub → Vercel → Web
```

### Code Modification — index.html → index2.html 주요 변경
- **색상 테마 변경**: 라이트 테마 → 다크 테마 (배경 `#f7f8fa`→`#0f1115`, 카드 `#ffffff`→`#1a1d24`)
- **강조색 변경**: 보라 `#6c5ce7` → 초록 `#00b894` (제목·링크·목록 점)
- **본문 가독성 개선**: 카드 본문·목록 글자색을 흰색(`#ffffff`)으로 바꿔 다크 배경 대비 확보
- **새 HTML 요소 추가**: "My GitHub" 카드 섹션 추가
- **외부 링크 추가**: 본인 GitHub(`github.com/22500349`) 링크 연결

### Problem & Solution
- **문제**: index가 있는 상태에서 index2를 만들면 일반적으로는 index2를 자동으로 배포하지 못했습니다.
- **해결**: AI를 통해 문제를 제시하고, Vercel 배포를 제어하는 JSON 파일(`vercel.json`)을 수정해 문제를 해결하였습니다.

### Reflection
- Git이 단순 백업이 아니라 "변경 이력을 시간순으로 관리하는 도구"라는 점을 새롭게 알게 되었습니다.
- 앞으로는 회원가입 정보를 DB에 저장·관리하는 백엔드 연동을 어떻게 구현할지 더 공부해보고 싶습니다.
