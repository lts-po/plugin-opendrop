## SPR opendrop plugin

*NOTE* in development

build and start
```sh
$ docker build -t opendrop .
$ docker run --rm -ti --privileged --network host opendrop bash
```

run inside the container
```sh
$ sudo owl -i <WLAN_IFACE>
$ opendrop find
```

## read more
https://github.com/seemoo-lab/owl
https://github.com/seemoo-lab/opendrop
