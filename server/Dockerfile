FROM node:14.4.0-alpine
WORKDIR '/app'
COPY ./package.json ./
RUN npm install --production
COPY . . 
EXPOSE 5000
CMD ["node", "index.js"]