FROM docker.io/frolvlad/alpine-oraclejdk8:latest
RUN mkdir -p /root/Mamello/sidecarProj /newrelic
RUN chmod 777 /newrelic
ADD newrelic /root/Mamello/sidecarProj/newrelic
ADD sleep.sh /root/Mamello/sidecarProj/sleep.sh
CMD ["/bin/sh","/root/Mamello/sidecarProj/sleep.sh"]
