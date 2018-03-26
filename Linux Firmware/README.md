# Linux Frimware

## Download firmware
```
wget -qO /lib/firmware/bnx2/bnx2-mips-06-6.2.3.fw https://github.com/Aniverse/BitTorrentClientCollection/raw/master/Linux%20Firmware/bnx2-mips-06-6.2.3.fw
wget -qO /lib/firmware/bnx2/bnx2-mips-09-6.2.1b.fw https://github.com/Aniverse/BitTorrentClientCollection/raw/master/Linux%20Firmware/bnx2-mips-09-6.2.1b.fw
wget -qO /lib/firmware/bnx2/bnx2-rv2p-09ax-6.0.17.fw https://github.com/Aniverse/BitTorrentClientCollection/raw/master/Linux%20Firmware/bnx2-rv2p-09ax-6.0.17.fw
wget -qO /lib/firmware/bnx2/bnx2-rv2p-09-6.0.17.fw https://github.com/Aniverse/BitTorrentClientCollection/raw/master/Linux%20Firmware/bnx2-rv2p-09-6.0.17.fw
wget -qO /lib/firmware/bnx2/bnx2-rv2p-06-6.0.15.fw https://github.com/Aniverse/BitTorrentClientCollection/raw/master/Linux%20Firmware/bnx2-rv2p-06-6.0.15.fw
ls /lib/firmware/bnx2 2>/dev/null
```

## Dpkg
```
wget -q https://github.com/Aniverse/BitTorrentClientCollection/raw/master/Linux%20Firmware/firmware-bnx2_20161130-3_all.deb
dpkg -i firmware-bnx2_20161130-3_all.deb && rm firmware-bnx2_20161130-3_all.deb
```
