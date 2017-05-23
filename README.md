# [libpurperl](https://github.com/fenollp/libpurperl)

`libpurperl` is a port for erlang that allows you to interface with the libpurple library.
`libpurple` is a library for interacting with many different instant messaging protocols and is part of the [pidgin project](http://pidgin.im).

## Requirements

* `rebar3` & Erlang/OTP ≥ 19.3 (untested with earlier versions)
* `sudo apt install libpurple-dev`

## Notes

This library is currently in a very early stage of development, but contribitions are welcome.

Right now, I'm aiming for one port per account logon - if you want to connect to
multiple accounts start a seperate port for each. This is to provide
fault-tolerance and to make the port itself vastly simpler.
