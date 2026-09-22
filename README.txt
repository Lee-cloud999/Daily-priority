Daily Priority PWA

GitHub 저장소 루트에 아래 파일을 모두 업로드하세요.
- index.html
- manifest.webmanifest
- service-worker.js
- icon-192.png
- icon-512.png

Firebase: 기존 maeum-jogak2 프로젝트의 이메일/비밀번호 Authentication 및 Firestore를 사용합니다.
데이터 경로: users/{uid}/daily_priority/{YYYY-MM-DD}
백업 경로: users/{uid}/daily_priority_backups/{backup-id}

처음 로그인할 때 이 브라우저의 기존 daily-priority 로컬 기록 중 클라우드에 없는 날짜는 자동 업로드됩니다. 이후 같은 계정으로 로그인한 기기끼리 Firestore를 통해 동기화됩니다.
