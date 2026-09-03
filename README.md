# My Profile Page

AI를 활용해 자기소개 웹페이지를 만들고, Git/GitHub 버전 관리와 Vercel 배포까지 실습한 프로젝트입니다.

## 프로젝트 설명

- `index.html` — AI를 활용하여 처음 생성한 자기소개 원본 페이지
- `index2.html` — 원본을 복사한 뒤 색상·글꼴·내용·요소를 직접 수정한 페이지
- 제작자: 선승범 (22500349, AI컴퓨터 전자 / 전산심화)

## Deploy URL

| 구분 | URL |
|---|---|
| Vercel Deploy | https://XXXXX.vercel.app |
| index.html | https://XXXXX.vercel.app/index.html |
| index2.html | https://XXXXX.vercel.app/index2.html |

> Vercel 배포 완료 후 `XXXXX` 부분을 실제 주소로 교체하세요.

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
- **글꼴·배경색 변경**: 밝은 파랑 테마 → 어두운(다크) 테마 + monospace 글꼴
- **헤더 색상 변경**: 단색 파랑 → 그린-블루 그라디언트
- **자기소개 텍스트 수정**: About Me 문구를 새 내용으로 교체
- **HTML 요소·외부 링크 추가**: `<h3>`와 References 섹션을 새로 만들고 MDN·Vercel 등 외부 사이트 링크 추가

### Problem & Solution
- **문제**: 로컬에서 만든 파일을 GitHub에 올려도 웹에서 확인할 방법이 없었습니다.
- **해결**: GitHub Repository를 Vercel에 Import하여 배포하니 URL로 접속 가능해졌고, 이후 Push할 때마다 자동 배포되도록 연결했습니다.

### Reflection
- Git이 단순 백업이 아니라 "변경 이력을 시간순으로 관리하는 도구"라는 점을 새롭게 알게 되었습니다.
- 앞으로는 회원가입 정보를 DB에 저장·관리하는 백엔드 연동을 어떻게 구현할지 더 공부해보고 싶습니다.
