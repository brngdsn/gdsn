FROM silarsis/yeoman

RUN git clone https://github.com/braungoodson/egclock

WORKDIR /home/yeoman/egclock

RUN git checkout develop
RUN bower install
RUN npm install
CMD npm start
