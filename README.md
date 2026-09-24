# 📚 공부 정리 (science-study)

중학교 시험 대비용 요약 + 예상문제를 웹페이지로 만들어 폰에서 앱처럼 보는 프로젝트.

## 🔗 링크 (폰에서 열기)

**https://naiad35.github.io/science-study/**

- 이 링크를 카톡 "나에게 보내기"로 보내고 폰에서 누르면 앱처럼 열림
- 아이폰: Safari로 열고 → 공유 📤 → "홈 화면에 추가" 하면 진짜 앱 아이콘처럼 사용 가능

## 📂 파일 구성

| 파일 | 설명 |
|------|------|
| `index.html` | 첫 화면 (요약/문제 선택 버튼) |
| `summary.html` | 핵심 요약 (쉬운 설명 + 생활 예시) |
| `quiz.html` | 예상문제 42문제 (풀면 바로 채점 + 해설) |

## 📖 현재 담긴 내용

- **과목**: 중1 과학 2학기
- **범위**: 여러 가지 힘 · 기체의 성질 · 물질의 상태 변화
  (2022 개정 교육과정, 천재교과서 기준 예상 범위 / 교과서 113~190쪽)

## 🚀 GitHub에 올리는 방법 (수정 후 반영)

파일을 고친 뒤 아래처럼 하면 링크에 바로 반영됨. (링크 주소는 그대로 유지)

```bash
cd ~/Documents/science-study
git add .
git commit -m "수정 내용"
git push
```

- 인증(토큰)은 **macOS 키체인에 이미 저장**돼 있어서 다시 입력할 필요 없음.
- push 후 1~2분이면 링크에 반영됨.

## 🔑 토큰 정보 (인증)

- GitHub 토큰이 macOS **키체인**에 저장되어 있음 (host: github.com / user: naiad35)
- 토큰이 만료되거나 새로 만들면, 아래로 키체인 갱신:
  ```bash
  printf "protocol=https\nhost=github.com\nusername=naiad35\npassword=새토큰\n\n" | git credential-osxkeychain store
  ```
- 토큰 관리 페이지: https://github.com/settings/tokens

## 📝 앞으로 추가할 과목 (예정)

- [ ] 국어
- [ ] 수학

> 새 과목은 폴더로 추가하거나, 원하는 방식으로 구성 가능.
