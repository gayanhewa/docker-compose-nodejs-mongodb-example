FROM hypriot/rpi-node:0.12.0

ADD package.json /code/
WORKDIR /code
RUN npm install
ADD . /code

CMD ["./node_modules/.bin/coffee", "./server.coffee"]
