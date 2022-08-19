FROM node:16.17.0
RUN mkdir -p /app
WORKDIR /app
# COPY ./proxy/package.json ./
# RUN npm ci -qy
COPY . .
CMD [ "npm", "run", "start" ]