yarn init -y
code .
yarn add express
yarn add -D @types/express typescript ts-node-dev
yarn tsc --init --> tsconfig (strict: false) (target: es2017)
yarn add prisma -D
yarn prisma init --> .env , prisma folder(schema.prisma)
Github OAuth app
yarn add dotenv (variaveis de ambiente)

app.get("/signin/callback", (request, response) => {
const { code } = request.query;
return response.json(code);
});

yarn add axios
yarn add @types/axios -D

yarn add jsonwebtoken
yarn add @types/jsonwebtoken -D

yarn prisma migrate dev
yarn add @prisma/client

yarn add socket.io
yarn add @types/socket.io -D

yarn add cors
yarn add @types/cors -D
