FROM scratch
COPY goblin /usr/bin/goblin
ADD plugins /goblin/plugins/
ADD static  /goblin/static/
ADD goblin.yaml /goblin/
ADD qqwry.dat /goblin/
WORKDIR /goblin
ENTRYPOINT ["/usr/bin/goblin"]
