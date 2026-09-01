# FormWheel

---KO---

🎡 FormWheel

브라우저에서 바로 쓰는 심플한 추첨 돌림판 웹앱입니다. Google forms에서 "형식은 [보고싶은거-이름-본인확인코드]으로 적어주셔야 합니다."라고 적으면 응답->요약에서 한번에 복사하여 이 돌림판에 복붙할 수 있다.

✨ 기능
항목 추가: 대괄호로 여러 개를 한 번에 입력하거나 ([인터스텔라] [듄] [기생충]), 줄바꿈으로 한 줄씩 입력
숨김 메모: [영화A-메모-1234]처럼 -를 쓰면 화면에는 영화A만 보이고, 당첨 후 팝업이 닫히면 나머지(메모-1234)가 하단에 작게 표시됨
항목별 크기 조절: 각 항목마다 1~10 크기를 설정해 돌림판 칸 크기와 당첨 확률을 다르게 지정 가능
회전 설정: 회전 시간(초), 회전 수(속도) 직접 조절
당첨 팝업: 큰 팝업 + 폭죽/불꽃놀이 효과, 팝업에서 바로 해당 항목 삭제 가능
팝업 스타일 선택: 골드 / 화려한 그라디언트 / 미니멀 중 선택
전체 삭제 / 효과 초기화: 항목 전체 삭제, 회전·팝업 설정 기본값으로 초기화
데이터 저장: 브라우저의 localStorage에 자동 저장되어 새로고침해도 유지됨 (기기·브라우저별로 별도 저장)
🚀 사용법
온라인으로 바로 쓰기 (GitHub Pages)
이 저장소의 Settings → Pages에서 main 브랜치를 배포 소스로 지정
발급된 주소(https://사용자명.github.io/저장소명/)로 접속
로컬에서 쓰기

index.html 파일을 더블클릭해서 브라우저로 열면 바로 실행됩니다. 별도 설치나 빌드가 필요 없습니다.

🛠️ 기술 스택
Vanilla HTML / CSS / JavaScript (프레임워크·빌드 도구 없음)
데이터 저장: 브라우저 localStorage
📁 파일 구성
.
├── index.html   # 앱 전체 (마크업 + 스타일 + 로직)
└── README.md
⚠️ 참고
데이터는 오직 해당 브라우저에만 저장됩니다. 다른 기기나 브라우저에서는 항목이 보이지 않으며, 브라우저 저장공간을 지우면 함께 삭제됩니다.
여러 명이 함께 쓰는 공용 서버 저장 기능은 포함되어 있지 않습니다.
📄 라이선스

자유롭게 사용, 수정, 배포하셔도 됩니다.

---EN---

🎡 FormWheel

A simple raffle/spinner web app you can use right in your browser. It's a single HTML file with no server or build step, so it can be hosted directly on GitHub Pages or any static hosting.

Tip: In your Google Form, add an instruction like "Please enter your answer in this format: [what you want-your name-your verification code]." Then in Forms → Responses → Summary, you can copy the responses in one go and paste them straight into this wheel.

✨ Features
Add entries: Enter multiple items at once using brackets ([Interstellar] [Dune] [Parasite]), or one per line without brackets
Hidden notes: Using a - like [MovieA-note-1234] shows only MovieA on screen; after the winner popup closes, the rest (note-1234) appears small below the footer
Per-item size: Set a size of 1–10 for each entry to change its slice size on the wheel and its odds of winning
Spin settings: Adjust spin duration (seconds) and spin count (speed)
Winner popup: A large popup with confetti/fireworks effects; you can delete the winning entry directly from the popup
Popup style options: Choose between Gold / Bold Gradient / Minimal
Clear all / Reset effects: Clear all entries, or reset spin and popup settings back to defaults
Data storage: Automatically saved to the browser's localStorage, so it persists across refreshes (storage is per device/browser)
🚀 Usage
Use it online (GitHub Pages)
In this repository, go to Settings → Pages and set main as the deployment branch
Visit the generated URL (https://your-username.github.io/repo-name/)
Use it locally

Just double-click index.html to open it in your browser. No installation or build step required.

🛠️ Tech Stack
Vanilla HTML / CSS / JavaScript (no framework, no build tools)
Data storage: browser localStorage
📁 File Structure
.
├── index.html   # the entire app (markup + styles + logic)
└── README.md
⚠️ Notes
Data is stored only in that specific browser. It won't appear on other devices or browsers, and clearing browser storage will delete it.
There is no shared/server-side storage for multiple people to use together.
📄 License

Free to use, modify, and distribute
