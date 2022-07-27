FROM node:alpine
WORKDIR /app
COPY package* ./
EXPOSE 3000
RUN npm install
COPY . .
CMD ["npm", "run", "dev"]
