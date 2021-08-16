# Use an existing docker image as a base
FROM node:alpine

# Create a Work Directory
WORKDIR /usr/app

#Copy files into container
COPY ./ ./

# Download and install a dependency
RUN npm install

# Tell the image what to do when it starts
# as a container	
CMD ["npm", "start"]