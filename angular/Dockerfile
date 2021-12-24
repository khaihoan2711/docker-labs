FROM node:16.13.1-alpine

WORKDIR /app/angular

COPY . .
RUN npm install
RUN npm install -g @angular/cli

CMD ng serve --host 0.0.0.0
EXPOSE 4200