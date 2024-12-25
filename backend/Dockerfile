FROM node:20.15.0-alpine3.20
EXPOSE 8080
ENV DB_HOST=mysql
RUN addgroup-Sexpense&&adduser-Sexpense-Gexpense
RUN mkdir/opt/server
RUN chownexpense:expense-R/opt/server
WORKDIR /opt/server
COPY package.json.
COPY *.js .
RUN npm install
CMD ["node","index.js"]


