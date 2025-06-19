FROM node:18

RUN npm install -g expo-cli

WORKDIR /app
COPY . .

RUN npm install

EXPOSE 19000 19001 19002
CMD ["expo", "start", "--tunnel"]
