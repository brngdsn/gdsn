FROM silarsis/yeoman

RUN git clone https://github.com/braungoodson/egtransclude

WORKDIR /home/yeoman/egtransclude

RUN git checkout develop
RUN bower install
RUN npm install
CMD npm start
