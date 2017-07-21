# PJSUA agent with JSON interface
Simple PJSUA (PJSIP User Agent) SIP user agent with JSON control interface

## Building

You need the following libs and tools:
  - Make
  - C and C++ compiler
  - libjson-c

With this installed, you should be able build everything by running `make`.
The makefile will autofetch the pjsip library and build it.

## Running

Running the generated binary with no arguments will give you the usage information.
```
Usage: ./basic_agent username password domain clientport [loglevel]
```
The arguments should be self-explanatory.