FROM alpine
RUN dd if=/dev/urandom of=/junk bs=1024 count=1000000 && echo 'moar' >> /junk && rm /junk
