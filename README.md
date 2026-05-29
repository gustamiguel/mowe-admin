# mowe-admin

Interface web administrativa do TCC MOWE, publicada no Cloudflare Workers Static Assets.

## Ambiente

- Node.js 24+.
- Wrangler via `npx wrangler`.
- Login Cloudflare: `npx wrangler whoami`.
- Desenvolvimento local: `npx wrangler dev`.
- Validar deploy sem publicar: `npx wrangler deploy --dry-run`.
- Publicar: `npx wrangler deploy`.

## Estrutura

- `public/index.html`: interface web.
- `public/favicon.ico`: icone do site.
- `wrangler.jsonc`: configuracao do Worker `mowe-admin`.
