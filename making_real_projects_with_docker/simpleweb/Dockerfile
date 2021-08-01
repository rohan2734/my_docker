#specify base image 
FROM node:alpine

WORKDIR /usr/app
#Install some dependencies
COPY ./package.json ./
#only copy from package.json

RUN npm install 
COPY ./ ./
#everything from current working directory from simple web to 
#current working directory inside the container 
 

#Default Command
CMD ["npm","start"]

