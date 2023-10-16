FROM node:16-alpine
WORKDIR /app/back-end
ADD /node_modules.tar.gz .
COPY . .
ENTRYPOINT ["npm"]
CMD [ "start" ]
EXPOSE 3001
