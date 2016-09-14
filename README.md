# neocon
A tiny program use for UART console by Openmoko

## Installation
Just run
```
$ make
```

## Usage
To connect to the UART use
```
$ ./neocon <ttyUSB_device> -b <baud_rate>
```
For example
```
$ ./neocon /dev/ttyUSB0 -b 115200
```
To quit neocon type
```
~.
```

original made by [Openmoko](http://wiki.openmoko.org/wiki/NeoCon)
