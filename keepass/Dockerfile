FROM ubuntu

RUN apt-get update
RUN apt-get install -y kpcli

WORKDIR /data

ENTRYPOINT ["/usr/bin/kpcli"]
CMD ["--kdb=db.kdb"]
