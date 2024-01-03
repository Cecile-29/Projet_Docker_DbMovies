FROM node:20-slim
WORKDIR /home/webflix
COPY ./webflix-master .

RUN npm i
EXPOSE 80
CMD ["npm", "start"]