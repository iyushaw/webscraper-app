# base image
FROM node:18.16.0-alpine
WORKDIR /app
# ADD /app/node_modules/.bin to $PATH
# ENV PATH /app/node_modules/.bin:$PATH
COPY package.json /app/package.json
RUN npm install
# RUN npm install @vue/cli@latest -g
CMD [“npm”, “run”, “serve”]
EXPOSE 9000
