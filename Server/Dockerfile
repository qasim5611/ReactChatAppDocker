FROM node:slim
LABEL maintainer="qmuhammad144@gmail.com"
WORKDIR /app
COPY . /app
RUN npm install
ENV CREATEDBY="Muhammad Qasim"
EXPOSE 5050
ENTRYPOINT ["node", "./app.js"]