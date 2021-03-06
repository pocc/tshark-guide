---
title: "Pcap Format"
description: Libpcap format, industry default
date: 2019-07-06
author: Ross Jacobs

summary: ''
weight: 20
draft: false
---

## Pcap

Pcap as a format was born at the same time as tcpdump/libpcap which used it. Technically, this would place place it at 1988 when tcpdump was created. However, I think it's fairer to place it at 1999 when tcpdump.org was launched and became more well-known.

Pcap is the most common capture type because libpcap has had support and been around for more than 20 years.
As an older format, it allocates fewer fields for packet and capture metadata.

## Pcap Links

### Pcap Docs

* 2015-08, Guy Harris, Wireshark's [Libpcap File Format](https://wiki.wireshark.org/Development/LibpcapFileFormat)
* Tcpdump, [Link-Layer Header Types](https://www.tcpdump.org/linktypes.html)

### Libpcap Programming

* 2002, Tim Carstens, [Programming with pcap](https://www.tcpdump.org/pcap.html)
* 2001, Martin Casado, [Packet Analysis](http://yuba.stanford.edu/~casado/pcap/section4.html)
