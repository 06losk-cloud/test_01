# test_01
ms 강의 중 스네이크 게임 코드 by html
브라우저에서 실행되는 스네이크 게임(Snake Game) 입니다.
하나의 HTML 파일(snake.html) 안에 HTML + CSS + JavaScript가 모두 포함되어 있어, 별도의 빌드 설정 없이 바로 실행할 수 있습니다.

🎮 특징 (Features)

단일 HTML 파일 구조
Canvas 기반 렌더링
**키보드 화살표(← ↑ → ↓)**로 조작
먹이를 먹으면 길이 증가 + 점수 증가
점수 5점마다 자동 속도 증가
벽 충돌 또는 자기 몸 충돌 시 게임 오버
최고 점수(localStorage) 자동 저장
반응형 UI (데스크탑/모바일 브라우저에서 모두 실행 가능)


📁 파일 구성 (File Structure)
/
│── snake.html   # HTML, CSS, JS가 모두 포함된 단일 파일
│── README.md    # 프로젝트 설명 파일


🚀 실행 방법 (How to Run)
1. 직접 실행

이 저장소를 다운로드 또는 클론합니다.
snake.html 파일을 브라우저(Chrome, Edge, Firefox 등)에서 열기만 하면 됩니다.

snake.html → 더블클릭

2. 로컬 서버에서 실행 (선택)
Shell# Python3 실행python3 -m http.server더 많은 선 표시
브라우저에서 http://localhost:8000 열기

🧩 조작 방법 (Controls)





































키기능⬆️ (Arrow Up)위로 이동⬇️ (Arrow Down)아래로 이동⬅️ (Arrow Left)왼쪽 이동➡️ (Arrow Right)오른쪽 이동▶️ 버튼게임 시작 / 재시작⏸️ 버튼일시정지🔁 버튼리셋

📷 스크린샷 (Screenshots)

필요하시면 이미지 파일을 추가해드릴 수 있어요!

(예시)
assets/
 ├── screenshot-gameplay.png
 └── screenshot-gameover.png


🛠️ 구현 포인트 (Technical Notes)

Canvas 2D API 를 사용해 격자 기반 게임 루프 구현
setInterval() 로 일정 간격 이동 처리
키 입력 버퍼(queue)로 급선회 시 자연스러운 방향 전환
충돌 판정:

벽 범위 벗어남 체크
뱀 몸통 배열과 head 좌표 비교


최고 점수는 localStorage.setItem() / getItem()으로 저장
CSS 변수(:root) 기반의 색상 테마 구성


🧱 향후 개선 기능 (To-Do)

 벽 통과 모드(토로이드 / wrap-around)
 장애물 추가
 사운드 효과
 색상 / 테마 커스텀 메뉴
 게임 스킨 선택 기능
 모바일 터치 전용 조작 UI 강화


📄 라이선스 (License)
MIT License
원하는 프로젝트에 자유롭게 사용·수정·배포 가능합니다.

🙌 기여 (Contributing)
Pull Request, Issue 모두 환영합니다!
버그 제보 또는 기능 요청이 있다면 언제든 알려주세요.
