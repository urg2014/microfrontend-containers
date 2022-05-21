FROM node:14

COPY . .

RUN cd frontend \
  && npm i \ 
  && npm run build

CMD ["node", "frontend/startup.js"]