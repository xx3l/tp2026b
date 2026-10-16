FROM alpine:latest
COPY ./app/ /app
RUN apk add nodejs npm
WORKDIR /app
RUN npm i
EXPOSE 5173
CMD ["npm", "run", "dev"]
