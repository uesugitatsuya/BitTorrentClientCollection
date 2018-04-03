# Xanmod

## Xanmod 4.12
```
wget --no-check-certificate https://github.com/Aniverse/BitTorrentClientCollection/raw/master/Xanmod/4.12.14-xanmod15/linux-image-4.12.14-xanmod15_1.170920_amd64.deb
wget --no-check-certificate https://github.com/Aniverse/BitTorrentClientCollection/raw/master/Xanmod/4.12.14-xanmod15/linux-headers-4.12.14-xanmod15_1.170920_amd64.deb
dpkg -i linux-image-*xanmod*.deb linux-headers-*xanmod*.deb && rm -rf *.deb
```

## Xanmod 4.15
```
wget --no-check-certificate https://github.com/Aniverse/BitTorrentClientCollection/raw/master/Xanmod/4.15.13-xanmod12/linux-image-4.15.13-xanmod12_1.180325_amd64.deb
wget --no-check-certificate https://github.com/Aniverse/BitTorrentClientCollection/raw/master/Xanmod/4.15.13-xanmod12/linux-headers-4.15.13-xanmod12_1.180325_amd64.deb
dpkg -i linux-image-*xanmod*.deb linux-headers-*xanmod*.deb && rm -rf *.deb
```

## Firmware and Microcode
```
wget --no-check-certificate https://github.com/Aniverse/BitTorrentClientCollection/raw/master/Xanmod/intel-microcode_3.20180312.1_amd64.deb
wget --no-check-certificate https://github.com/Aniverse/BitTorrentClientCollection/raw/master/Xanmod/iucode-tool_2.3.1-1_amd64.deb
wget --no-check-certificate https://github.com/Aniverse/BitTorrentClientCollection/raw/master/Xanmod/linux-firmware_1.161_all.deb
dpkg -i *.deb && rm -rf *.deb
```

## Xanmod 4.15 via apt
```
echo 'deb http://deb.xanmod.org releases main' | tee /etc/apt/sources.list.d/xanmod-kernel.list
wget -qO- http://deb.xanmod.org/gpg.key | apt-key add -
apt-get update && apt-get install -y linux-xanmod-4.15 intel-microcode iucode-tool
```

## Source

https://xanmod.org  
https://sourceforge.net/projects/xanmod/files/  
