# 전민규 · Backend Engineering Portfolio

노션 포트폴리오의 내용으로 만든 반응형 HTML 사이트입니다.

- 사이트: https://minggure.github.io/
- 원문: https://www.notion.so/3cf09199440481d99843ee97e7080b35
- 구성: 자기소개, 기술, CLUTCH / MINGPARK / DAENGGO, 활동·수상, 개발 원칙
- 외부 라이브러리나 빌드 없이 `index.html`을 브라우저에서 열면 됩니다.

## 사진 넣기

1. `assets/`에 본인 사진을 `profile.jpg`라는 이름으로 넣습니다.
2. `index.html`에서 `src="assets/profile.svg"`를 `src="assets/profile.jpg"`로 바꿉니다.
3. 같은 이미지의 `alt`를 `전민규 프로필 사진`으로 바꿉니다.
4. 커밋하고 `gh-pages` 브랜치로 push하면 GitHub Pages에 반영됩니다.

사진은 4:5 비율로 표시됩니다. 얼굴 위치는 `.photo-frame img`에 `object-position: center 30%;`처럼 지정할 수 있습니다.

## 내용 수정과 배포

본문과 CSS·JavaScript는 `index.html`에 포함돼 있습니다. 노션 변경 사항은 자동 동기화되지 않습니다.
GitHub Pages는 `gh-pages` 브랜치의 `/` 경로를 게시합니다.
별도의 npm 설치, 백엔드 서버, 비밀값이 필요하지 않습니다.

## PDF

페이지 아래의 ‘PDF로 저장 / 인쇄’를 누르고 브라우저 인쇄 대상에서 PDF를 선택합니다.
인쇄할 때는 기술적 판단의 접이식 상세 설명이 모두 펼쳐집니다.

## 자료 기준

수치와 역할은 제공된 노션 문서를 기준으로 옮겼습니다.
CLUTCH의 20,000명 결과는 60초 Ramp 테스트이며, 쿼리 구간과 API 응답, 부하 발생기 네트워크 개선을 구분해 표기했습니다.
MINGPARK와 DAENGGO에 확인되지 않은 성능 수치를 추가하지 않았습니다.
