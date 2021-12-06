FROM node:14-alpine

WORKDIR /database
EXPOSE 3001
ADD node_modules.tar.gz ./
COPY ./ ./

ENTRYPOINT [ "npm" ]
CMD [ "start" ]
