FROM fusuf/whatsasena:latest

RUN git clone https://github.com/ChamodKeshan/Alexa-New /root/ales
WORKDIR /root/ales/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "install.js"]
