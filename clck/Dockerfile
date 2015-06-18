FROM silarsis/yeoman

RUN git clone https://github.com/braungoodson/egclock

WORKDIR /home/yeoman/egclock

RUN git checkout develop
RUN npm install
RUN npm start
