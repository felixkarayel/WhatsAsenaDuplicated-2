FROM fusuf/whatsasena:latest

RUN git clone https://oguz25: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@github.com/phaticusthiccy/WhatsAsenaDuplicated-1 /root/WhatsAsenaDuplicated-1
WORKDIR /root/WhatsAsenaDuplicated-1/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
