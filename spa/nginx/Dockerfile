
FROM node:24

WORKDIR /spa:

COPY . .

RUN rm -rf node_modules
RUN npm i

CMD ["npm", "start"]

EXPOSE 5173
