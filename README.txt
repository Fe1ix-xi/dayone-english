DAYONE English — 대학 과제용 웹앱 프로토타입

실행 방법
1. index.html 파일을 Chrome, Edge, Whale 등 최신 브라우저에서 엽니다.
2. 인터넷 연결이 있으면 Google Fonts가 로드됩니다. 음성 재생은 브라우저의 SpeechSynthesis 지원에 따라 달라집니다.
3. 닉네임 랭킹은 현재 브라우저의 localStorage에 저장되는 데모입니다.

웹에 공개하는 방법 (무료 정적 호스팅 예시: GitHub Pages)
1. GitHub에 새 공개 저장소(repository)를 만듭니다.
2. index.html을 저장소 최상위(root)에 업로드합니다.
3. 저장소 Settings > Pages > Build and deployment에서 Deploy from a branch를 선택합니다.
4. Branch를 main, 폴더를 /(root)로 지정하고 Save를 누릅니다.
5. 잠시 후 https://사용자명.github.io/저장소명/ 주소로 접속할 수 있습니다.

프로토타입 범위 및 한계
- 단어, 유사어, 발음 표기, 이모지 이미지, 음성 재생(SpeechSynthesis), 리스닝/문법/독해 퀴즈, 상황별 스피킹 답변 입력 및 코칭 시연, 모의토익, 로컬 랭킹, 잠금화면 위젯 미리보기를 포함합니다.
- AI 발음 분석/실시간 AI 회화, 서버 기반 공동 랭킹, 실제 모바일 잠금화면 위젯, 푸시 알림은 구현하지 않았습니다.
- 음성 악센트는 브라우저/운영체제에 설치된 음성에 따라 달라질 수 있습니다. 성별·연령을 보장하지 않습니다.
- 랭킹은 서버가 없는 로컬 시연용이며, 다른 사용자의 기기와 공유되지 않습니다.
- 실제 서비스로 확장하려면 백엔드, 데이터베이스, 인증, AI 음성 API, 네이티브 위젯/알림 구현이 필요합니다.
