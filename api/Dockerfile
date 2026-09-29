# ---------- Stage 1: build ----------
FROM node:24-alpine3.24 AS build
# ele criar a pasta caso nao exista
WORKDIR /usr/src/app/
# estou copiando os arquivos de dependências primeiro para aproveitar o cache do Docker
COPY package*.json ./
# instala todas as dependências (incluindo devDependencies, necessárias para o build)
RUN npm ci
# copia o codigo
COPY . .
# compila o TypeScript para dist/
RUN npm run build

# ---------- Stage 2: production ----------
FROM node:24-alpine3.24 AS production
WORKDIR /usr/src/app/
ENV NODE_ENV=production
COPY package*.json ./
# instala somente as dependências de produção, reduzindo o tamanho final da imagem
RUN npm ci --omit=dev
# copia apenas o resultado do build do estágio anterior
COPY --from=build /usr/src/app/dist ./dist
# evita rodar a aplicação como root
USER node
# boa pratica
EXPOSE 3000

CMD ["node", "dist/main"]