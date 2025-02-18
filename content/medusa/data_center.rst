---
title: Data Center
weight: 290
---

We have 5U in one of the racks in the G26 data center. It houses the backup
server (Thunk).

.. class:: dc-rack

+-----+----+-----------------+-------------+-----------------------------------+
| PWR | U# | Name            | Inventory # | Overview                          |
+=====+====+=================+=============+===================================+
|     | 4  |                 | (likely     | 9x 4TB drives / 12x bays          |
+     +----+ JBOD (Thunk)    | part of     |                                   |
|     | 5  |                 | 264097,000) |                                   |
+-----+----+-----------------+-------------+-----------------------------------+
|     | 6  |                 |             |                                   |
+     +----+                 | 261309,000  | 2x 6-core 2.4 GHz Xeon E5645      |
|     | 7  | Thunk           |             | 96 GiB RAM                        |
+     +----+                 |             |                                   |
|     | 8  |                 |             | 12x 4TB drives / 16x bays         |
+-----+----+-----------------+-------------+-----------------------------------+

In the G01 data center, we own a 42U rack. The contents of the rack are (as of
2018.08.09):

.. class:: dc-rack

+-----+----+-----------------+-------------+-----------------------------------+
| PWR | U# | Name            | Inventory # | Overview                          |
+=====+====+=================+=============+===================================+
|     | 1  |                 |             |                                   |
+ N/C +----+ UPS             | 243181,000  | 1000 VA                           |
|     | 2  |                 |             |                                   |
+-----+----+-----------------+-------------+-----------------------------------+
|     | 3  | Router          | 1019378     | SG-8860                           |
+-----+----+-----------------+-------------+-----------------------------------+
|     | 4  | DMZ Switch      |             | 48 Port HP V1910-48G              |
+-----+----+-----------------+-------------+-----------------------------------+
|     | 5  | Cable Management|             |                                   |
+-----+----+-----------------+-------------+-----------------------------------+
|     | 6  | Mgmt. Switch    |             | 24 Port HP ProCurve 1700-24       |
+-----+----+-----------------+-------------+-----------------------------------+
|     | 7  | Cable Management|             |                                   |
+-----+----+-----------------+-------------+-----------------------------------+
|     | 8  | Data Switch     | 1019379     | 28 Port Netgear XS728T            |
+-----+----+-----------------+-------------+-----------------------------------+
|     | 9  |                 |             |                                   |
+-----+----+-----------------+-------------+-----------------------------------+
|     | 10 | Mulder          | 260876,000  | 1x 4-core 3.2 GHz Xeon E3-1230    |
+     +----+                 |             | 16 GiB RAM                        |
|     | 11 |                 |             |                                   |
+-----+----+-----------------+-------------+-----------------------------------+
|     | 12 |                 |             |                                   |
+-----+----+-----------------+-------------+-----------------------------------+
|     | 13 |                 |             |                                   |
+-----+----+-----------------+-------------+-----------------------------------+
|     | 14 |                 |             |                                   |
+-----+----+-----------------+-------------+-----------------------------------+
|     | 15 |                 |             |                                   |
+-----+----+-----------------+-------------+-----------------------------------+
|     | 16 |                 |             |                                   |
+-----+----+-----------------+-------------+-----------------------------------+
|     | 17 |                 |             |                                   |
+-----+----+-----------------+-------------+-----------------------------------+
|     | 18 |                 |             |                                   |
+-----+----+-----------------+-------------+-----------------------------------+
|     | 19 |                 |             |                                   |
+-----+----+-----------------+-------------+-----------------------------------+
|     | 20 |                 |             |                                   |
+-----+----+-----------------+-------------+-----------------------------------+
|     | 21 |                 |             |                                   |
+-----+----+-----------------+-------------+-----------------------------------+
|     | 22 |                 |             | Sun Fire T2000                    |
+ N/I +----+ Sunshine        + 252757,000  + 1x 8-core 1.2GHz                  +
|     | 23 |                 |             | 16 GiB RAM                        |
+-----+----+-----------------+-------------+-----------------------------------+
|     | 24 |                 |             |                                   |
|     |    |                 |             |                                   |
+-----+----+-----------------+-------------+-----------------------------------+
|     | 25 |                 |             | 2x 10-core 2.3 GHz Xeon E5-2650v3 |
+     +----+ snake11         + 1019380,000 + 96 GiB DDR4 RAM                   +
|     | 26 |                 |             |                                   |
+-----+----+-----------------+-------------+-----------------------------------+
|     | 27 | snake10         | 267616,000  | 4x 8-core 2.8 GHz Opteron 6320    |
|     |    |                 |             | 512 GiB RAM                       |
+-----+----+-----------------+-------------+-----------------------------------+
|     | 28 | snake9          | 246831,000  | 1x 8-core 2.0 GHz Opteron 6128    |
|     |    |                 |             | 64 GiB RAM                        |
+-----+----+-----------------+-------------+-----------------------------------+
|     | 29 |                 | 245075,000  | 1x 4-core 2.67 GHz i7 920         |
+     +----+ snake8          |             | 18 GiB RAM                        |
|     | 30 |                 |             |                                   |
+-----+----+-----------------+-------------+-----------------------------------+
|     | 31 | snake7          |             | 4x 16-core 2.4 GHz Opteron 6272   |
|     |    |                 |             | 256 GiB RAM                       |
+-----+----+-----------------+-------------+-----------------------------------+
|     | 32 | snake5 & snake6 | 261309,000  | each snake:                       |
+-----+----+-----------------+ (guessing)  |                                   |
|     | 33 | snake3 & snake4 |             | 2x 6-core 2.4 GHz Xeon E5645      |
+-----+----+-----------------+             | 96 GiB RAM                        |
|     | 34 | snake1 & snake2 |             |                                   |
+-----+----+-----------------+-------------+-----------------------------------+
| PDU | 35 | Medusa          | 265021,000  | 4x 8-core 2.8 GHz Opteron 6320    |
+ \&  +----+                 +             + 256 GiB RAM                       +
| UPS | 36 |                 |             |                                   |
+-----+----+-----------------+-------------+-----------------------------------+
| PDU | 37 | Zing            | 1031333     | 13x 3.84TiB SanDisk Optimus 2 Max |
+ \&  +----+                 |             | / 24x bays                        |
| UPS | 38 |                 |             |                                   |
+-----+----+-----------------+-------------+-----------------------------------+
| PDU | 39 | JBOD (Zing)     | 265526,000  | 6x 4TB HDD / 12x bays             |
+ \&  +----+                 |             |                                   |
| UPS | 40 |                 |             |                                   |
+-----+----+-----------------+-------------+-----------------------------------+
|     | 41 |                 |             |                                   |
+     +----+ UPS             |             | 3000 VA                           |
|     | 42 |                 |             |                                   |
+-----+----+-----------------+-------------+-----------------------------------+

The rack's Inventory Nr.: 248252,00

Legend:

* N/I: *not installed* (physically **not** in the rack)
* N/C: *not connected* (physically in the rack)
