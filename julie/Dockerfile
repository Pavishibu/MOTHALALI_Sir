FROM quay.io/lyfe00011/test:beta

RUN git clone https://github.com/Pavi_kunjan/MOTHALALI_Sir_v2 /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
RUN yarn install --no-audit
RUN git clone https://github.com/Pavishibu/MOTHALALI_Sir_v2
RUN cp -R /root/Utils/* /root/WhatsAsenaDuplicated 
CMD ["node", "bot.js"]
