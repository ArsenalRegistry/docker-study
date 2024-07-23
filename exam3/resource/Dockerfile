FROM debian
RUN apt-get update; apt-get install stress -y
CMD ["/bin/sh", "-c", "stress -c 2"]
