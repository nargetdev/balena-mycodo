FROM influxdb:1.8

RUN mkdir -pv /var/influxdb/data

COPY influxdb/run.sh /run.sh
RUN chmod +x /*.sh

ENV PRE_CREATE_DB mycodo_db
ENV ADMIN_USER mycodo
ENV PASS mmdu77sj3nIoiajjs

EXPOSE 8086

CMD /run.sh
