pb - HTTP server benchmarking tool written in Perl
==================================================

pb is a tool for benchmarking your Hypertext Transfer Protocol (HTTP) server.

(not ab compatibility)

Usage
-----

```sh
$ pb --uri http://example.com [--con 10 --time 60 --debug]
  uri             request uri             (required
  con             concurrency             (default 1
  time            benchmark running time  (default 3 
  debug           output debug log        (default 0
```

See Also
--------

- http://gihyo.jp/dev/serial/01/perl-hackers-hub/001703

