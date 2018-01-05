ansible installed in ubuntu
===========================

## CMD

`docker build -t ansible-ubuntu14.04 .`


## NOTE

https://github.com/moby/moby/issues/27988 to solve this:

```
debconf: unable to initialize frontend: Dialog
debconf: (TERM is not set, so the dialog frontend is not usable.)
debconf: falling back to frontend: Readline
debconf: unable to initialize frontend: Readline
debconf: (This frontend requires a controlling tty.)
debconf: falling back to frontend: Teletype
dpkg-preconfigure: unable to re-open stdin:
```