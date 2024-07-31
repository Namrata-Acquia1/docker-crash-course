FROM node:17-alpine 
# parent image or base layer

WORKDIR /app
# specify working directory

COPY . .
# copy from relative folder to root directory on img or specific folder COP . . OR COPY . /app

RUN npm install
# Add all dependencies e.g npm install

EXPOSE 4000
# Document that the application inside the container will listen on port 4000

CMD ["node", "app.js"]
# To run application