FROM node:10

VOLUME  ["/home/toegyi/Docker-Test/angular-dev/my-dream-app"]

WORKDIR /home/toegyi/Docker-Test/angular-dev/my-dream-app

RUN apt-get update

#install project dependencies
COPY ./my-dream-app/package.json /home/toegyi/Docker-Test/angular-dev/my-dream-app
RUN npm install
RUN npm install -g @angular/cli

#add app
COPY . /home/toegyi/Docker-Test/angular-dev/my-dream-app

EXPOSE 3000

#install project dependencies when container starts
CMD npm install
