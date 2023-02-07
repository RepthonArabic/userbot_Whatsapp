FROM rogerpq/userbot_Whtsapp
RUN git clone https://github.com/RepthonArabic/userbot_Whtsapp /root/rogerpq
WORKDIR /root/rogerpq/
RUN npm install npm@latest
RUN yarn install --network-concurrency 1
EXPOSE 8000
CMD ["npm", "start"]
