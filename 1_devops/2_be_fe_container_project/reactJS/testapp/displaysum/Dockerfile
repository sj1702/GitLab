FROM node:20.11.1
WORKDIR /displaysum/
COPY public/ /displaysum/public
COPY src/ /displaysum/src
COPY package.json /displaysum/
RUN npm install
RUN npm i bootstrap
CMD ["npm", "start"]

