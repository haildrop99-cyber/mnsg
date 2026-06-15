MNSG Cloudflare 배포 패키지

구성:
- dist/index.html : Stitch 코드보기에서 나온 실제 웹페이지 파일
- wrangler.toml : Cloudflare Workers Static Assets 설정
- package.json : wrangler deploy 실행용

Cloudflare Workers & Pages에서 설정:
1. GitHub에 이 폴더 구조 그대로 업로드
2. Build command: 비워두거나 npm install
3. Deploy command: npx wrangler deploy
4. Root directory: /
5. 먼저 mnsg.haildrop99.workers.dev 정상 표시 확인
6. 정상 표시 후 Settings > Domains & Routes에서 mnsgstudio.com Custom Domain 연결

주의:
- DESIGN.md 또는 txt 파일만 업로드하면 사이트가 열리지 않습니다.
- 반드시 dist/index.html 파일이 있어야 합니다.
*test
