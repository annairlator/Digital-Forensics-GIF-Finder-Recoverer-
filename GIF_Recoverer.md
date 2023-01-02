# GIF Signature Finder

This project is a recoverer that uses the location of a known GIF file signature in a NTFS file system to recover the GIF file.

## Prerequisite Software

* gcc
* make

## Building

To build using make, run the following command while inside the ```GIFRecoverer``` directory:
```
make
```

## Running

Once built using the above steps, the project can be executed as follows while in the same directory as ```makefile```:
```
./a.out <device or volume path> <physical address of GIF signature>
```
Examples of valid devices and volumes:
* ```/dev/sda```
* ```/dev/sda1```
* ```VolumeImage.iso```

The address should be a physical byte-address in hex value (e.g. ```0x0000000f298000```). This address is the same value outputted by the GIF finder project.