## iousniffer

A tool which intercepts traffic on IOU netio sockets and writes it to pcap
files.

#### Build

```
sudo aptitude install libpcap-dev build-essential
make
```

#### Usage

```
./iousniff -i /tmp/netio1000 -s . -f -ddddd
```

Note: Don't run `iousniff` with `sudo`.

#### Notes

The `iousniff` program has been super useful for https://github.com/kholia/my-pcaps work.

This program was tested with `i86bi_linux-adventerprisek9-ms.154-2.T.bin` in
September-2021 on an Ubuntu 21.04 box.
