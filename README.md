# vps-benchmarks
## Contabo
```
# ## ## ## ## ## ## ## ## ## ## ## ## ## ## ## ## ## #
#              Yet-Another-Bench-Script              #
#                     v2021-06-05                    #
# https://github.com/masonr/yet-another-bench-script #
# ## ## ## ## ## ## ## ## ## ## ## ## ## ## ## ## ## #

Sa 3. Jul 23:56:12 CEST 2021

Basic System Information:
---------------------------------
Processor  : Intel(R) Xeon(R) CPU E5-2630 v4 @ 2.20GHz
CPU cores  : 4 @ 2199.998 MHz
AES-NI     : ✔ Enabled
VM-x/AMD-V : ❌ Disabled
RAM        : 7.8 GiB
Swap       : 2.0 GiB
Disk       : 195.8 GiB

fio Disk Speed Tests (Mixed R/W 50/50):
---------------------------------
Block Size | 4k            (IOPS) | 64k           (IOPS)
  ------   | ---            ----  | ----           ----
Read       | 5.28 MB/s     (1.3k) | 63.83 MB/s     (997)
Write      | 5.30 MB/s     (1.3k) | 64.27 MB/s    (1.0k)
Total      | 10.59 MB/s    (2.6k) | 128.10 MB/s   (2.0k)
           |                      |
Block Size | 512k          (IOPS) | 1m            (IOPS)
  ------   | ---            ----  | ----           ----
Read       | 127.58 MB/s    (249) | 97.70 MB/s      (95)
Write      | 134.36 MB/s    (262) | 104.21 MB/s    (101)
Total      | 261.94 MB/s    (511) | 201.92 MB/s    (196)

iperf3 Network Speed Tests (IPv4):
---------------------------------
Provider        | Location (Link)           | Send Speed      | Recv Speed
                |                           |                 |
Clouvider       | London, UK (10G)          | 197 Mbits/sec   | 200 Mbits/sec
Online.net      | Paris, FR (10G)           | 198 Mbits/sec   | 200 Mbits/sec
WorldStream     | The Netherlands (10G)     | 197 Mbits/sec   | 200 Mbits/sec
Biznet          | Jakarta, Indonesia (1G)   | 168 Mbits/sec   | 133 Mbits/sec
Clouvider       | NYC, NY, US (10G)         | 180 Mbits/sec   | 152 Mbits/sec
Velocity Online | Tallahassee, FL, US (10G) | 171 Mbits/sec   | 189 Mbits/sec
Clouvider       | Los Angeles, CA, US (10G) | 179 Mbits/sec   | 185 Mbits/sec
Iveloz Telecom  | Sao Paulo, BR (2G)        | 164 Mbits/sec   | 181 Mbits/sec

Geekbench 5 Benchmark Test:
---------------------------------
Test            | Value
                |
Single Core     | 503
Multi Core      | 1553

```
## Hetzner
```
# ## ## ## ## ## ## ## ## ## ## ## ## ## ## ## ## ## #
#              Yet-Another-Bench-Script              #
#                     v2021-06-05                    #
# https://github.com/masonr/yet-another-bench-script #
# ## ## ## ## ## ## ## ## ## ## ## ## ## ## ## ## ## #

Sun 04 Jul 2021 12:04:27 AM CEST

Basic System Information:
---------------------------------
Processor  : Intel Xeon Processor (Skylake, IBRS)
CPU cores  : 1 @ 2100.000 MHz
AES-NI     : ✔ Enabled
VM-x/AMD-V : ❌ Disabled
RAM        : 1.9 GiB
Swap       : 0.0 KiB
Disk       : 18.7 GiB

fio Disk Speed Tests (Mixed R/W 50/50):
---------------------------------
Block Size | 4k            (IOPS) | 64k           (IOPS)
  ------   | ---            ----  | ----           ----
Read       | 108.13 MB/s  (27.0k) | 1.17 GB/s    (18.4k)
Write      | 108.42 MB/s  (27.1k) | 1.18 GB/s    (18.5k)
Total      | 216.55 MB/s  (54.1k) | 2.36 GB/s    (36.9k)
           |                      |
Block Size | 512k          (IOPS) | 1m            (IOPS)
  ------   | ---            ----  | ----           ----
Read       | 2.31 GB/s     (4.5k) | 2.93 GB/s     (2.8k)
Write      | 2.44 GB/s     (4.7k) | 3.13 GB/s     (3.0k)
Total      | 4.76 GB/s     (9.2k) | 6.06 GB/s     (5.9k)

iperf3 Network Speed Tests (IPv4):
---------------------------------
Provider        | Location (Link)           | Send Speed      | Recv Speed
                |                           |                 |
Clouvider       | London, UK (10G)          | 3.19 Gbits/sec  | 5.79 Gbits/sec
Online.net      | Paris, FR (10G)           | 7.54 Gbits/sec  | 6.51 Gbits/sec
WorldStream     | The Netherlands (10G)     | 10.0 Gbits/sec  | 5.06 Gbits/sec
Biznet          | Jakarta, Indonesia (1G)   | 766 Mbits/sec   | 107 Mbits/sec
Clouvider       | NYC, NY, US (10G)         | 1.84 Gbits/sec  | 1.77 Gbits/sec
Velocity Online | Tallahassee, FL, US (10G) | 1.89 Gbits/sec  | 1.58 Gbits/sec
Clouvider       | Los Angeles, CA, US (10G) | 1.09 Gbits/sec  | 1.03 Gbits/sec
Iveloz Telecom  | Sao Paulo, BR (2G)        | 312 Mbits/sec   | 877 Mbits/sec

iperf3 Network Speed Tests (IPv6):
---------------------------------
Provider        | Location (Link)           | Send Speed      | Recv Speed
                |                           |                 |
Clouvider       | London, UK (10G)          | 5.44 Gbits/sec  | 6.67 Gbits/sec
Online.net      | Paris, FR (10G)           | 7.73 Gbits/sec  | 5.49 Gbits/sec
WorldStream     | The Netherlands (10G)     | 7.72 Gbits/sec  | 5.44 Gbits/sec
Clouvider       | NYC, NY, US (10G)         | 1.47 Gbits/sec  | 1.85 Gbits/sec
Clouvider       | Los Angeles, CA, US (10G) | 943 Mbits/sec   | 1.05 Gbits/sec

Geekbench 5 Benchmark Test:
---------------------------------
Test            | Value
                |
Single Core     | 691
Multi Core      | 700
Full Test       | https://browser.geekbench.com/v5/cpu/8671929

``` 

## Netcup
```
 ## ## ## ## ## ## ## ## ## ## ## ## ## ## ## ## ## #
#              Yet-Another-Bench-Script              #
#                     v2021-06-05                    #
# https://github.com/masonr/yet-another-bench-script #
# ## ## ## ## ## ## ## ## ## ## ## ## ## ## ## ## ## #

Sat Jul  3 23:55:17 CEST 2021

Basic System Information:
---------------------------------
Processor  : QEMU Virtual CPU version 2.5+
CPU cores  : 2 @ 2399.994 MHz
AES-NI     : ✔ Enabled
VM-x/AMD-V : ❌ Disabled
RAM        : 3.9 GiB
Swap       : 0.0 KiB
Disk       : 39.3 GiB

fio Disk Speed Tests (Mixed R/W 50/50):
---------------------------------
Block Size | 4k            (IOPS) | 64k           (IOPS)
  ------   | ---            ----  | ----           ----
Read       | 64.36 MB/s   (16.0k) | 655.48 MB/s  (10.2k)
Write      | 64.48 MB/s   (16.1k) | 658.93 MB/s  (10.2k)
Total      | 128.85 MB/s  (32.2k) | 1.31 GB/s    (20.5k)
           |                      |
Block Size | 512k          (IOPS) | 1m            (IOPS)
  ------   | ---            ----  | ----           ----
Read       | 757.18 MB/s   (1.4k) | 949.28 MB/s    (927)
Write      | 797.41 MB/s   (1.5k) | 1.01 GB/s      (988)
Total      | 1.55 GB/s     (3.0k) | 1.96 GB/s     (1.9k)

iperf3 Network Speed Tests (IPv4):
---------------------------------
Provider        | Location (Link)           | Send Speed      | Recv Speed
                |                           |                 |
Clouvider       | London, UK (10G)          | 854 Mbits/sec   | 458 Mbits/sec
Online.net      | Paris, FR (10G)           | 860 Mbits/sec   | 410 Mbits/sec
WorldStream     | The Netherlands (10G)     | 845 Mbits/sec   | 441 Mbits/sec
Biznet          | Jakarta, Indonesia (1G)   | 676 Mbits/sec   | 81.4 Mbits/sec
Clouvider       | NYC, NY, US (10G)         | 781 Mbits/sec   | 379 Mbits/sec
Velocity Online | Tallahassee, FL, US (10G) | 758 Mbits/sec   | 279 Mbits/sec
Clouvider       | Los Angeles, CA, US (10G) | 753 Mbits/sec   | 340 Mbits/sec
Iveloz Telecom  | Sao Paulo, BR (2G)        | 504 Mbits/sec   | 138 Mbits/sec

iperf3 Network Speed Tests (IPv6):
---------------------------------
Provider        | Location (Link)           | Send Speed      | Recv Speed
                |                           |                 |
Clouvider       | London, UK (10G)          | 806 Mbits/sec   | 562 Mbits/sec
Online.net      | Paris, FR (10G)           | busy            | 267 Mbits/sec
WorldStream     | The Netherlands (10G)     | 859 Mbits/sec   | 340 Mbits/sec
Clouvider       | NYC, NY, US (10G)         | 800 Mbits/sec   | 358 Mbits/sec
Clouvider       | Los Angeles, CA, US (10G) | 743 Mbits/sec   | 314 Mbits/sec

Geekbench 5 Benchmark Test:
---------------------------------
Test            | Value
                |
Single Core     | 510
Multi Core      | 707
Full Test       | https://browser.geekbench.com/v5/cpu/8671863
```
