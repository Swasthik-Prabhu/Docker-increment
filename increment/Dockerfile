# base file
FROM node:16

#  workdir
WORKDIR /App

# copy the dependency
COPY package*.json ./

# install it 
RUN npm install 

# copy
COPY . . 

# port number
EXPOSE 5173

# ENV
ENV NODE_ENV=production

# to run
CMD ["npm", "run", "dev"]