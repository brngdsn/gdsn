FROM silarsis/yeoman

RUN git clone https://github.com/braungoodson/egtransclude

WORKDIR /home/yeoman/egtransclude

RUN git checkout develop
RUN npm install
RUN bower install
CMD npm start
