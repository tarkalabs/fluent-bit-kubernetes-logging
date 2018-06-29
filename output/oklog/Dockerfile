FROM fluent/fluent-bit:0.13.4

ADD https://github.com/oklog/oklog/releases/download/v0.3.2/oklog-0.3.2-linux-amd64 /fluent-bit/bin/oklog
RUN ["chmod", "775", "/fluent-bit/bin/oklog"]
COPY run.sh /run.sh
CMD ["/run.sh"]
