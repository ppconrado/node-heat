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
