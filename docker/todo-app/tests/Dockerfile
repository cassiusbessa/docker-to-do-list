FROM mjgargani/puppeteer:trybe1.0
WORKDIR /home/node/app
COPY package*.json ./
RUN npm install
COPY . ./
CMD ["npm", "start"]
