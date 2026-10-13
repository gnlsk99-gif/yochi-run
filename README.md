# YO-CHI RUN
사진 참고 캐릭터를 Canvas로 직접 그린 모바일 팬 게임입니다. 원본 사진이나 인물 사진은 게임에 포함되지 않습니다.

## 플레이
화면/점프 버튼 또는 스페이스/위쪽 화살표로 점프. 공중에서 한 번 더 점프 가능.
딸기·망고·쿠키·모찌 각각 2개 이상 모아 매장까지 도착하면 클리어.
하트 3개, 약 50초. 일시정지·재도전·9:16 결과 PNG 저장 포함.
통계 및 온라인 순위는 포함하지 않습니다.

## GitHub → Vercel
새 저장소 yochi-run 생성 → 이 폴더 안 파일을 저장소 루트에 업로드 → Commit changes.
Vercel에서 해당 저장소 Import. Framework Other, Build Command 비움, Output Directory `.`.
Deploy 후 GitHub 수정 커밋 시 자동 배포.
이전 게임 폴더나 ZIP 자체를 올리지 마세요.

## 파일
index.html 화면 / style.css 디자인 / engine.js 규칙·레벨·물리 / game.js 그림·입력·저장.
index.html을 브라우저로 열어 로컬 플레이도 가능합니다.
