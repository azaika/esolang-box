FROM esolang/python2

RUN git clone --depth 1 https://github.com/gvx/suzy.git ~/suzy && \
    ln -s /bin/script /bin/suzy && \
    rm /bin/python2

COPY script /root/script
