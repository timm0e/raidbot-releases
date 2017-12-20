FROM node:latest

RUN npm i -g --unsafe-perm https://github.com/timm0e/raidbot-releases/releases/download/latest/raidbot-web-latest.tgz

EXPOSE 3000

ENV NODE_ENV production

CMD raidbot-web
