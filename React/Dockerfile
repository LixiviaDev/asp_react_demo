FROM node:19.0.0

WORKDIR /usr/src/app

ARG FRONTEND_TEMPLATE_REPO

RUN git clone ${FRONTEND_TEMPLATE_REPO} .
RUN git pull

RUN npm install -g n
RUN n 18
RUN npm install
RUN npm run build