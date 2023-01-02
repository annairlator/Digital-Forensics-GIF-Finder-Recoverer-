# GIF Signature Finder

This project is a scanner that locates potential GIF files based on magic numbers associated with the file type.

## Prerequisite Software

* gcc

## Building

To build using make, run the following command while inside the ```GIFFinder``` directory:
```
gcc scanStart.c
```

## Running

Once built using the above steps, the project can be executed as follows while in the same directory as ```makefile```:
```
./a.out <device or volume path>
```
Examples of valid devices and volumes:
* ```/dev/sda```
* ```/dev/sda1```
* ```VolumeImage.iso```