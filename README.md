"# nlw-10-copa"
BACKEND
npm init -y
npm i typescript -D
npx tsc --init
Modificar tsconfig.json para:
"target": "es2020"
Instalando Fastify
npm i fastify -D
npm i tsx -D
PRISMA BANCO DE DADOS
npm i prisma -D
npm i @prisma/client
npx prisma init --datasource-provider SQLite
npx prisma migrate dev
npx prisma studio
npm i prisma-erd-generator @mermaid-js/mermaid-cli -D
npx prisma generate
npm i @fastify/cors

FRONTEND

MOBILE
