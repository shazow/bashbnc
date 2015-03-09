# bashbnc

Single-User IRC bouncer (BNC) written in Bash.

**Status**: It sorta-works for the first connection, as a null bouncer. Second
connection is broken for now, having trouble spoofing the hostname in the
welcome message replay.


## Usage

```
$ ./bnc
IRC bouncer for a given HOST server.
Usage: ./bnc HOST [PORT]

$ ./bnc localhost 6667
Connecting to IRC server on localhost:6667.
Listening for IRC clients on localhost:16667.
```

## Goal

Lols.

Also trying to grok what the protocol for a BNC looks like.

But mostly lols.


## License

MIT.
