# bashbnc

Single-User IRC bouncer (BNC) written in Bash.

**Status**: It sorta-works for the first connection, as a null bouncer. Second
connection seems to work too.


## Usage

```
$ ./bnc
Single-user IRC bouncer (BNC) for a given IRC_HOST server.
Usage: ./bnc IRC_HOST [IRC_PORT [BNC_HOST [BNC_PORT]]]

$ ./bnc localhost 6667
Connecting to IRC server on localhost:6667.
Listening for IRC clients on localhost:16667.

$ ./bnc irc.freenode.net 6667 localhost 16667
Connecting to IRC server on irc.freenode.net:6667.
Listening for IRC clients on localhost:16667.
[relay]  :irc.freenode.net NOTICE * :*** Looking up your hostname...
...
```

Once the BNC is running, use your favourite IRC client to connect to it (running
on localhost:16667 by default). **There is zero security built in**, avoid exposing
your listening port to the public intertubes.

## Goal

Lols.

Also trying to grok what the protocol for a BNC looks like.

But mostly lols.


## License

MIT.
