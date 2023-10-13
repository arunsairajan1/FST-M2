#set the base image
FROM node:18-alpine

#set the working directory
WORKDIR /usr/app

#copy the files into container
COPY ./package.json ./

#install dependencies
RUN npm install

#copy rest of the files
COPY ./ ./

#start the web server
CMD ["npm", "start"]
