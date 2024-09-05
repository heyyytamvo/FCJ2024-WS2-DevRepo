FROM node:20-alpine3.20

WORKDIR /home/app

COPY . /home/app
# Debug
RUN ls /home/app
# Debug
RUN npm install
RUN npm run build

EXPOSE 3000

CMD ["npm", "run", "start"]