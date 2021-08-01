#Use an existing docker image as a base
FROM alpine 
#FROM,RUN,CMD are instructions



#Download and install  a dependency
RUN apk add --update gcc
RUN apk add --update redis


#Tell the image , what to do , when it starts as a contianer
CMD ["redis-server"] 
#argument to cmd

#run
#docker build .
#docker run <id>(a56f4cbd0f7556a6e4f2caa604f69)

#>ctrl+c to quit


#FROM is used   to specify  base image to the docker (using the specified image as a base image)
#RUN is used, to execute, some command, while we are building a custom image
#CMD specifies, what should be executed, when our image is used to build a new container


#FROM,RUN and CMD are most important
