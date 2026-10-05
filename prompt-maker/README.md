# 프롬프트 메이커

하고 싶은 일을 입력하고 AI(ChatGPT / Claude / Gemini / 기타)와 길이(짧게 / 보통 / 자세히)를 고르면, 해당 AI에 맞는 프롬프트를 만들어 주는 개인용 웹앱입니다.

- 순수 HTML / CSS / JavaScript (설치, 빌드, 서버 없음)
- 프롬프트 복사, 최근 기록 10개, 마지막 선택값 기억
- 기록과 설정은 사용 중인 브라우저의 localStorage에만 저장됩니다

## 실행

`index.html`을 브라우저에서 열면 됩니다.

## GitHub Pages로 배포

1. Settings → Pages
2. Source: Deploy from a branch
3. Branch: `main` / `(root)` 선택 후 Save
4. 1~2분 뒤 `https://<사용자명>.github.io/<저장소명>/` 접속
