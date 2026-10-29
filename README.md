# Prelude 식전영상 에디터 (prelude-studio)

GitHub 저장소에 아래 구조 그대로 올리면 Cloudflare Workers가 자동으로 배포해요.

```
prelude-studio/          ← 저장소 맨 위
├─ wrangler.jsonc        ← Worker 이름 "prelude-studio"
├─ README.md
└─ public/
   └─ index.html         ← 식전영상 에디터 (이 파일 하나가 프로그램 전체)
```

- `public/index.html` 은 식전영상 에디터예요. 무드앤클릭 홈페이지 파일과 이름이 같으니 섞이지 않게 주의하세요.
- 업데이트할 때는 `public/index.html` 만 새 파일로 덮어쓰면 돼요.
- 배포가 끝나면 사이트를 강력 새로고침(PC: Ctrl+Shift+R)하세요.
