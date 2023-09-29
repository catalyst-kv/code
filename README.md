## Hardware
- Nvidia GTX 1050 Ti or higher
- PCIe 3.0 x16 or faster
- DRAM 128 GB or more
- Disk space 2 TB or more
- SSD space 64 GB or more
## Software
- Ubuntu 18.04 or later
- MongoDB 4.2 or later
- CUDA 9.2 
- YCSB

## Setup
### Backend Datastore
Refer to guide: https://www.mongodb.com/docs/mongocli/stable/install

### CUDA
Refer to guide: https://docs.nvidia.com/cuda/cuda-installation-guide-linux/index.html

### Cache Server
```shell
$ sudo apt update
$ sudo apt-get install gcc make libevent-dev libc6-dev
$ git clone https://github.com/catalyst-kv/code.git
$ cd code/src
```
For in-memory cache server
```shell
$ ./configure
```
For memory-flash cache server
```shell
./configure --enable-extstore
```
```shell
$ make
$ sodu make install
```

### YCSB
Refer to guide: https://github.com/brianfrankcooper/YCSB/

Trace Generator: https://github.com/has-lab/YCSB-tracegen


