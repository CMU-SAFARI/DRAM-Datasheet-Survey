## DRAM Datasheet Survey and Analysis

This repository contains data about DRAM chip operating parameters extracted
from publicly-available DRAM chip datasheets spanning the history of commodity
DRAM from 1970 until present. Our description and analysis of this dataset can
be found in our academic paper [1].
 
*Please send questions to Minesh Patel at minesh.patelh@gmail.com*

## Dataset Overview

The data is organized as a comma-separated value (CSV) file with rows
representing different DRAM chips and the following columns describing each
chip:

+ Manufacturer
+ Model number
+ Speed bin
+ Datasheet URL
+ DRAM standard (e.g., SDRAM, DDRn)
+ Datasheet publication date (as a best-effort estimate of the chip introduction date)
+ Chip storage capacity
+ Number of DQ pins per chip package
+ I/O clock rate (bus and data)
+ DRAM refresh timings (number of refresh cycles, tREFw, tREFI, tRFC)
+ DRAM access timings (tRAC, tCAC, tAA, CL, tCCD, tRCD, tRAS, tRP, tRC, tWR)
+ Operating current measurements (IDD0, IDD1, IDD2P, IDD2N, IDD3P, IDD3N, IDD4R, IDD4W, IDD5B, IDD6N, IDD8)

We manually extract the aforementioned information to the best of our ability
and omit cells for which a given datasheet does not provide information.

## Attribution

Please cite our paper [1] if you use this data or otherwise find it helpful.

\[1\] Minesh Patel, Taha Shahroodi, Aditya Manglik, A. Giray Yaglikci, Ataberk Olgun, Haocong Luo, and Onur Mutlu, "A Case for Transparent Reliability in DRAM Systems", arXiv:2204.10378, 2022.
