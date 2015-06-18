FROM silarsis/yeoman

RUN git clone https://github.com/braungoodson/infinite-scrolling-reddit

WORKDIR /home/yeoman/infinite-scrolling-reddit

RUN git checkout frontyard
RUN bower install
RUN npm install
CMD npm start
