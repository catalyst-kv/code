## Hardware
- Nvidia GTX 1050 Ti or higher
- PCIe 3.0 x8 or faster
- DRAM 128 GB or more
- Disk space 1 TB or more
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
$ sudo apt update\
$ sudo apt-get install gcc make libevent-dev libc6-dev
$ git clone https://github.com/OCMLIKS/code


### YCSB
Refer to guide: https://github.com/brianfrankcooper/YCSB/

Trace Generator: https://github.com/has-lab/YCSB-tracegen

