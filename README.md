# 식전영상 에디터

- `public/index.html` : 편집 페이지 (각자 브라우저에서 작업, 서버 저장 없음)
- `wrangler.jsonc` : Cloudflare Workers 설정 (Worker 이름 `prelude-studio`)

작업은 각 기기 브라우저에 자동 저장되고, ‘작업 저장’으로 받은 .zip 파일을 ‘작업 불러오기’로 열면 이어서 편집할 수 있어요.
