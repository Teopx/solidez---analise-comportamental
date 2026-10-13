ACADEMIA INTEGRAR - DEPLOY CLOUDFLARE WORKERS

1. Extraia este ZIP.
2. Envie os arquivos e a pasta public para a raiz do seu repositorio GitHub.
3. Em Cloudflare Workers & Pages, conecte o repositorio.
4. Build command: deixe vazio.
5. Deploy command: npx wrangler deploy
6. Root directory: raiz do repositorio (onde esta wrangler.jsonc).

O arquivo public/index.html contem a aplicacao.
Se ja existir um wrangler.toml ou wrangler.jsonc antigo no repositorio, substitua a configuracao antiga para evitar conflitos.
