# Use an existing docker image as a base
# alpine is a linux os
FROM alpine

# Download and install a dependency
# apk is a apache package manager and we a updating redis since it is already present inbuilt in alpine 
RUN apk add --update redis
RUN apk add --update gcc

# Tell the image what to do when it starts
# as a container
CMD ["redis-server"]
