
FROM java:8
ADD cdsurvey-server-0.0.1-SNAPSHOT.jar  /root/
ADD default_cmd.sh /root/
RUN chmod +x default_cmd.sh
EXPOSE 8000
ENTRYPOINT /root/default_cmd.sh