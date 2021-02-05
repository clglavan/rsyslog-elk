FROM alwayslearn/tcpkali

COPY ./payload.json /payload.json

#ENTRYPOINT [ "bombardier -f payload.json -c 1 -n 100 http://rsyslog01:514" ]
# CMD ["-m","POST","-f","payload.json","-c","1","-n","100","http://rsyslog01:514"]
CMD ["tcpkali","-m","\"Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec consequat nisi laoreet nunc venenatis,\"","-c","10","rsyslog01:514"]