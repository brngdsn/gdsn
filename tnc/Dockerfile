FROM silarsis/yeoman

RUN git clone https://github.com/brngdsn/tonic

WORKDIR /home/yeoman/tonic

RUN git checkout frontyard
RUN bower install
RUN npm install
CMD grunt serve:dist --force
