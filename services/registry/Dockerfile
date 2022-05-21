FROM node:14-alpine
ENV NODE_ENV=production

COPY . .

RUN cd /api
RUN npm install --production\
RUN npm run build

CMD ["node", "/api/dist/index.js"]

