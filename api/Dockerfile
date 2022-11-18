FROM node:16-alpine

RUN npm install -g nodemon

# Create app directory
WORKDIR /app

COPY package.json .

RUN npm install

# Install app dependencies
COPY . .

EXPOSE 4000

CMD [ "npm", "run", "dev" ]

