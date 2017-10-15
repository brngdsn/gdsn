FROM silarsis/yeoman

RUN git clone https://github.com/brngdsn/qckblg

WORKDIR /home/yeoman/qckblg

RUN npm install
RUN bower install
CMD grunt serve:dist --force
