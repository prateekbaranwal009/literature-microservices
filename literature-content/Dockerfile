FROM node:18.0-slim
WORKDIR /pratilipi/content
COPY ./package*.json ./
RUN npm install
COPY . .
EXPOSE 3001
CMD [ "npm", "run", "start" ]