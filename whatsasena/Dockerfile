FROM fusuf/whatsasena:latest

RUN git clone https://felixkarayel:200I6PfRWJKvZintkhInhn9k+lcJ72TYDT6BoXQocko@github.com/felixkarayel/WhatsAsenaDuplicated-2 /root/WhatsAsenaDuplicated-2
WORKDIR /root/WhatsAsenaDuplicated-1/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
