FROM node:14
WORKDIR /opt/day1
ADD package.json /opt/day1/
RUN npm install
ADD . /opt/day1/
EXPOSE 3000
CMD ["node", "index.js"]