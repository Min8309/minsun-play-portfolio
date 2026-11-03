# PLAY NOTES · 박민선 게임 포트폴리오

논두잉, 경성게임, 찍고깨의 기획과 인터랙션을 소개하는 단일 페이지 게임 포트폴리오입니다.

## 공개 사이트

- 게임 포트폴리오: https://minsun-play-portfolio.minsunpark3421.chatgpt.site
- 전체 포트폴리오: https://parkminsunportfolio.vercel.app/

현재 공개 사이트는 ChatGPT Sites에서 배포됩니다. 이 GitHub 저장소는 소스 보관용이며, GitHub 변경이 공개 사이트에 자동 반영되지는 않습니다.

## 소개하는 프로젝트

1. **논두잉** — 3D 공간을 둘러보고 자리를 골라 60초 동안 생각을 내려놓는 휴식형 인터랙션
   - 소스: https://github.com/Min8309/non_doing
   - 실행 주소는 이 저장소 검토에서 확인하지 못해 포트폴리오에 소스 링크만 제공합니다.
2. **경성게임** — 1934년 경성의 인쇄소에서 기록을 읽고 단서를 연결하는 역사·공포 탐색 퍼즐
   - 실행: https://gyeongseong-game-min8309.minsunpark3421.chatgpt.site
   - 소스: https://github.com/Min8309/game_01
   - 팀 프로젝트: https://ejdms499-wq.github.io/gyeongseong-yarok_v/opening.html
3. **찍고깨** — 사진을 선택하고 터치한 위치부터 균열과 파편이 생기는 모바일 브라우저 콘텐츠
   - 실행: https://snapsmash.vercel.app/
   - 소스: https://github.com/Min8309/Snap_Break
   - 실행 주소는 원본 저장소에 등록된 주소이며, 이번 소스 저장 과정에서는 실제 모바일 카메라·음향·진동까지 재검증하지 않았습니다.

## 로컬에서 보기

`index.html`과 `assets/`의 게임 화면·굿즈 이미지로 구성된 정적 페이지입니다. 저장소를 내려받은 뒤 브라우저에서 파일을 열거나, 아래처럼 간단한 정적 서버로 확인할 수 있습니다.

```bash
python -m http.server 8000
```

그다음 `http://localhost:8000`에 접속합니다.

## 이미지 자료

- 세 게임의 대표 영역은 제공된 영상의 플레이 구간을 무음으로 반복 재생합니다. 화면 비율을 유지하며 영역 너비에 맞춰 표시하고, 재생 컨트롤로 일시 정지할 수 있습니다. 대표 정지 화면도 포스터 이미지로 제공합니다.
- 경성야록 굿즈 디자인 시트와 키링·마스킹테이프 활용 시안을 함께 소개합니다.
- 굿즈 이미지를 누르면 원본을 새 탭에서 볼 수 있습니다.

## 검증 범위

- 390px, 768px, 1440px 화면 폭에서 가로 넘침 확인
- 프로젝트 3개와 상세 설명 열기·닫기 확인
- JavaScript 실행 오류 및 외부 로컬 파일 의존성 확인
- 링크 형식과 목적지 주소 확인

실제 iPhone/Safari 성능, 논두잉의 배포 주소, 찍고깨의 카메라·음향·진동은 별도 실기기 확인이 필요합니다.
