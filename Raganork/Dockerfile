FROM BOLT-SER/BOLTSERBOT:test

RUN git clone https://github.com/BOLT-SER/BOLTSERBOT/ /BOLT/BOLTSERBOT
WORKDIR /BOLT/BOLTSERBOT 
ENV TZ = Asia/Kolkata
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "BOLTSERBOT.js"]
