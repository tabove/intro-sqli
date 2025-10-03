FROM node:14-slim

WORKDIR /app    
ADD . .
RUN npm i
ENTRYPOINT [ "node", "index.js" ]

ENV LANG=C.UTF-8
ENV LC_ALL=C.UTF-8