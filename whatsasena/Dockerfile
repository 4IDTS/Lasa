FROM fusuf/whatsasena:latest

RUN git clone https://github.com/4IDTS/Lasa
WORKDIR /root
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
