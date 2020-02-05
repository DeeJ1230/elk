FROM fluentd
USER root
# RUN cat "/fluentd/etc/fluent.conf"
COPY ./conf/fluent-dan.conf /fluentd/etc/fluent.conf 
RUN cat "/fluentd/etc/fluent.conf"
RUN ["gem", "install", "fluent-plugin-elasticsearch", "--no-rdoc", "--no-ri"]
