FROM silarsis/yeoman

RUN git clone https://github.com/brngdsn/qckblg

WORKDIR /home/yeoman/qckblg

RUN bower install
RUN npm install
CMD grunt serve:dist --force
