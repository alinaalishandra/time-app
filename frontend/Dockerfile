FROM node:alpine

WORKDIR /app

EXPOSE 3000
# ./ or /app/ - текущая директория куда копируем
COPY package*.json ./

RUN npm install

COPY . .
# запускаем скрипт "дев"
CMD [ "npm", "run", "dev" ]
