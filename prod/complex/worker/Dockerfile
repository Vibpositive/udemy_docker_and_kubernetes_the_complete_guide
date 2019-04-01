FROM node:lts-alpine
WORKDIR /app
copy ./package.json ./
RUN npm install
RUN npm audit fix
COPY . .
CMD ["npm", "run", "start"]