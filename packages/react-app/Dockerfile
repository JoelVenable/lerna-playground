FROM node:13.10-alpine3.10

WORKDIR /opt/hah
ADD build /opt/hah/build

RUN ["npm", "install", "-g", "serve"]

EXPOSE 3000
CMD serve -s -l 3000 build

