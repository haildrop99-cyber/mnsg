MNSG Cloudflare Workers 정적 사이트 패키지

GitHub에는 ZIP 파일 자체가 아니라 아래 파일/폴더를 루트에 업로드하세요.
- dist/index.html
- wrangler.toml
- package.json
- README_KR.txt

Cloudflare 설정:
Root directory: /
Build command: 비워두기
Deploy command: npx wrangler deploy
