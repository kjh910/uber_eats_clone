FROM node:16

WORKDIR /app

ADD ./nuber /app/

RUN npm install -g @nestjs/cli
RUN npm i

RUN chmod 777 /app/runserver.sh

CMD ["/app/runserver.sh"]