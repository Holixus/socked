
## build

```sh
cmake .
make
```

## install

```sh
make install
```

## usage

```
Usage: socked <options>

options:
  -s, --server=<ip:port>     : ip/port of peer server;
  -l, --listen=<ip:port>     : ip/port to listen of connections;
  -i, --iface=<interface>    : bind listen socket to the network interace;
  -d, --daemon               : start as daemon;
  -f, --pid-file=<filename>  : set PID file name;
  -h                         : print this help and exit.
```
