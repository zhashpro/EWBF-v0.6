# EWBF-v0.6 (Bitcoin Gold, Tent)
EWBF's CUDA Equihash Miner for NVIDIA GPU

## Quick Start Guide

Download the miner using the link below.

**NOTE**: Chrome browser may block the download. Use Mozilla Firefox or another browser.

[Download EWBF v0.6 CUDA 8 Windows Version](https://github.com/zhashpro/EWBF-v0.6/raw/main/EWBF%20CUDA%208%20Equihash%20Miner%20v0.6.rar)

[Download EWBF v0.6 CUDA 9.1 Windows Version](https://github.com/zhashpro/EWBF-v0.6/raw/main/EWBF%20CUDA%209.1%20Equihash%20Miner%20v0.6.rar)

Extract the archive and edit _ZHash-Start.bat_ file with your favorite text editor.

1. Set the --server _URL_ and --port _number_
2. Change _yourWallet_ to your wallet address
3. Save and exit

**Example for Bitcoin Gold**: miner.exe --algo 144_5 --pers BgoldPoW --server _eu1.zhash.pro_ --port _5058_ --user _yourwallet_.workername --pass x

**Example for Tent**: miner.exe --algo 144_5 --pers sngemPoW --server _eu1.zhash.pro_ --port _1058_ --user _yourwallet_.workername --pass x

Run EWBF Miner by double clicking _ZHash-Start.bat_

Approximate hash rates:

1080ti: ~75 Sols/s

1080  : ~50 Sols/s

1070  : ~45 Sols/s

1060  : ~30 Sols/s

1050ti: ~18 S/s
