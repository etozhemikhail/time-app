FROM node:alpine
WORKDIR /app
COPY package* ./
EXPOSE 5000
RUN npm install
COPY . .
CMD ["npm", "run", "dev"]
