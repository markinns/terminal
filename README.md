# terminal
A curated list of shell commands and tools for use in OS X.

## Table of Contents
- [Networking](#networking)
    - [ARP Table](#arptable)
- [Tools](#tools)
    - [FileMerge](#filemerge)

## Networking

### Local Network

#### Find IP and MAC addresses of local machines
Show the IP and MAC address of all devices on the network that have been successfully probed or connected to.
```bash
# ARP Table
arp -a
```

## Tools

### Compare and Merge Files or Directores

#### Compare using FileMerge utility in OS X
FileMerge can find the differences between two text files, as well as compare two directories with the ability to merge them into a single directory that eliminates duplicate files.
```bash
# opendiff
opendiff File1.rtf File2.rtf
```
