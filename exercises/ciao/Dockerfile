FROM node:5.7.1

COPY package.json /app/
WORKDIR /app
RUN npm install
COPY index.js /app/

ENV PORT 80
EXPOSE $PORT
CMD ["node", "/app/index.js"]
