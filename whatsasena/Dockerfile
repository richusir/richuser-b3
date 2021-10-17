FROM fusuf/whatsasena:latest

RUN git clone https://github.com/richusir/richuser-b3 /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/ 
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit
RUN git clone https://github.com/vishnu-memanakizhakathil/meenu

CMD ["node", "bot.js"]
