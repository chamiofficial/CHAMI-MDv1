FROM quay.io/sampandey001/secktor
RUN git clone https://github.com/SamPandey001/Secktor-Md/root/SamPandey001
WORKDIR /root/SamPandey001/
RUN yarn install --network-concurrency 1
EXPOSE 8000
CMD ["npm", "start"]
