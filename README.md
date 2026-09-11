# 전민규 · Backend Engineering Portfolio

노션 포트폴리오의 내용으로 만든 반응형 HTML 사이트입니다.

- 사이트: https://minggure.github.io/
- 원문: https://www.notion.so/3cf09199440481d99843ee97e7080b35
- 구성: 자기소개와 개발 원칙, 학력, 활동·수상, 기술, CLUTCH / MINGPARK / DAENGGO
- 외부 라이브러리나 빌드 없이 `index.html`을 브라우저에서 열면 됩니다.

## 프로필 사진

프로필 사진은 `assets/profile.jpg`에 있습니다. 같은 파일을 교체하면 사진을 바꿀 수 있습니다.
화면에서는 4:5 비율로 표시하며, 얼굴 위쪽이 잘리지 않도록 상단을 기준으로 배치합니다.

## 화면 구성과 가독성

- 본문은 데스크톱과 모바일 모두 16px, 표는 14~15px로 표시합니다.
- 좁은 화면의 표는 글자를 줄이는 대신 가로로 스크롤합니다. 키보드로 표에 초점을 맞춘 뒤 방향키로 이동할 수 있습니다.
- 프로젝트 목록에서 이름·역할·검증 결과를 확인하고 상세 설명으로 이동할 수 있습니다.
- 기술적 판단은 접이식 설명으로 제공하며, 인쇄할 때 펼치고 인쇄 후 원래 상태로 복원합니다.
- 정량 결과와 근거 링크는 유지하고 제목 위 반복 라벨과 장식용 박스를 줄였습니다.

## 내용 수정과 배포

본문과 CSS·JavaScript는 `index.html`에 포함돼 있습니다. 노션 변경 사항은 자동 동기화되지 않습니다.
GitHub Pages는 `gh-pages` 브랜치의 `/` 경로를 게시합니다.
별도의 npm 설치, 백엔드 서버, 비밀값이 필요하지 않습니다.

## 글꼴과 인쇄

본문은 함께 제공하는 Pretendard 가변 글꼴을 사용합니다. 첫 소개 문장은 PC에서 20px, 모바일에서 18px로 표시합니다.
글꼴 라이선스는 `assets/Pretendard-LICENSE.txt`에 있습니다.
별도 인쇄 버튼은 제공하지 않으며, 브라우저 기본 인쇄 기능을 사용할 수 있습니다.
인쇄할 때는 기술적 판단의 접이식 상세 설명이 모두 펼쳐집니다.

## 자료 기준

수치와 역할은 제공된 노션 문서를 기준으로 옮겼습니다.
CLUTCH의 20,000명 결과는 60초 Ramp 테스트이며, 쿼리 구간과 API 응답, 부하 발생기 네트워크 개선을 구분해 표기했습니다.
MINGPARK와 DAENGGO에 확인되지 않은 성능 수치를 추가하지 않았습니다.

## 프로젝트 이미지와 색상

목차·요약 목록·상세 본문은 CLUTCH → MINGPARK → DAENGGO 순서입니다.

| 프로젝트 | 이미지 출처 | 색상 |
| --- | --- | --- |
| CLUTCH | [README 로고](https://github.com/seok-cess/Clutch-BE/blob/9949870b036bf29ffd0edd999212a38cca142ed6/docs/assets/clutch-logo.png) | 로고의 보라색 |
| DAENGGO | [로그인 일러스트](https://github.com/meongkk/daenggo-FE/blob/3d59590a59b7d3bad558ca233e9feef70b364206/src/assets/LoginDog.png) | 프론트의 주황색 브랜드 토큰 |
| MINGPARK | [README 로고](https://github.com/minggure/Mingpark/blob/4584041fb995997fecea80ef8c70ef4369631f0a/src/main/resources/static/images/mingpark-logo.png) | 로고의 연두색 |

DAENGGO의 README에는 대표 이미지가 없어 실제 프론트엔드 로그인 일러스트를 사용했습니다. README의 서비스명은 멍크크이며, 포트폴리오의 프로젝트명 DAENGGO를 유지했습니다.
이미지는 `assets/`에 원본 그대로 보관합니다. 링크와 제목에는 흰 배경에서 읽기 쉬운 진한 색조를 적용하고 본문 색은 유지합니다.
