FROM quay.io/sampandey001/secktor
RUN git clone https://github.com/kanishkadesilva/QUEEN-THARU-MD-V1 /root/kanishkadesilva
WORKDIR /root/kanishkadesilva/
RUN npm install npm@latest
RUN npm install
EXPOSE 8000
CMD ["npm", "start"]
