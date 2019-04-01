FROM node:lts-alpine
WORKDIR /app
copy ./package.json ./
RUN npm install
COPY . .
CMD ["npm", "run", "start"]