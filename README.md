Features
--------

- Automatically generate sessions (based on command and working directory)

Dependencies
------------

- [dtach][]

Installation
------------

1. Download the [script](bin/attach)
2. Place it on your `$PATH` (`~/bin` is a good choice if it is on your path)
3. Set it to be executable (`chmod +x <file>…`)

Usage
-----

```
attach [option]… <token>
```

Tokens
------

- `directory`: list attachable sockets
- `socket`: attach to socket
- `command`: attach or create new session

Options
-------

- `-help`: display a help message and quit

[dtach]: http://dtach.sourceforge.net
