FROM node:16.18.0-alpine
# Create app directory
WORKDIR /usr/src/app
# Install app dependencies
COPY package*.json ./

RUN npm install
# Copy app source code
COPY . /usr/src/app


#Expose port and start application
EXPOSE 8080

CMD [ "npm", "start" ]

