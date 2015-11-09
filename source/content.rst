============================================
Chapter 2 Network Standard and the OSI model
============================================

********
Checksum
********
TCP in the source computer sends a character string called checksum based on the content of the data to the destination. TCP on the destination then generates a similar string . If the two checksum fail to match, the destinatinon ask the source to reransmit the data.

Its a method of error checking that determines if the contents of an arriving data unit matches the content of the data unit sent by source.

**********
Sequencing
**********
Sequencing is the method used by TCP that ensures the packet received are assembled in the correct order. TCP attaches a chronological sequencing number to each segment so that the destination host can reorder the packets if necessary.

*********************************
Error Checking in Data Link Layer
*********************************
Data link layer adds redundant bits to the frame called CRC. The receiver also generates this CRC based on the content and then matches it. If it fails then there has been data loss.

=======================
Chapter 8: Wireless LAN
=======================

*************************
Placement of Access Point
*************************

Placemen of access point must take into account the typical distance between access point and its clients.

==============		====
802.11 b and g 		100m
802.11a				20m
802.11n				400m
==============		====

It should also consider the type and numbero of obstacles between access oints and clients. It must also make sure its not close to potential source of interference.



