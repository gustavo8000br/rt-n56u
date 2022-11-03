# README #

![CI](https://github.com/gustavo8000br/rt-n56u/workflows/CI/badge.svg)
![GitHub All Releases](https://img.shields.io/github/downloads/gustavo8000br/rt-n56u/total)
[![release](https://img.shields.io/github/release/gustavo8000br/rt-n56u.svg)](https://github.com/gustavo8000br/rt-n56u/releases)

Welcome to the rt-n56u project

This project aims to improve the rt-n56u and other supported devices on the software part, allowing power user to take full control over their hardware.
This project was created in hope to be useful, but comes without warranty or support. Installing it will probably void your warranty. 
Contributors of this project are not responsible for what happens next.

## How do I get set up? ##

* [Get the tools to build the system](https://bitbucket.org/padavan/rt-n56u/wiki/EN/HowToMakeFirmware) or [Download pre-built system image](https://bitbucket.org/padavan/rt-n56u/downloads)
* Feed the device with the system image file (Follow instructions of updating your current system)
* Perform factory reset
* Open web browser on http://my.router to configure the services

### Contribution guidelines ###

* To be completed

***

### Special Note ###
* Chinese dictionary from：https://github.com/gorden5566/padavan
* Changelog：https://www.jianshu.com/p/d76a63a12eae

***

### Firmware Features ###

* use [gorden5566](https://github.com/gorden5566/padavan) Chinese dictionary
* aria2 front end replaced with [AriaNg](https://github.com/mayswind/AriaNg)
* [curl](https://github.com/curl/curl) Optional compiled executable program ```CONFIG_FIRMWARE_INCLUDE_CURL```
* used [PROMETHEUS](http://pm.freize.net/index.html) Some patches provided
* used [Linaro1985/padavan-ng](https://gitlab.com/padavan-ng/padavan-ng) part of the package
* The following plugins are optional：
* [scutclient](https://github.com/hanwckf/scutclient) ```CONFIG_FIRMWARE_INCLUDE_SCUTCLIENT```
* [gdut-drcom](https://github.com/chenhaowen01/gdut-drcom) ```CONFIG_FIRMWARE_INCLUDE_GDUT_DRCOM```
* [dogcom](https://github.com/hanwckf/dogcom) ```CONFIG_FIRMWARE_INCLUDE_DOGCOM```
* [minieap](https://github.com/hanwckf/minieap) ```CONFIG_FIRMWARE_INCLUDE_MINIEAP```
* [njit-client](https://github.com/hanwckf/njit8021xclient) ```CONFIG_FIRMWARE_INCLUDE_NJIT_CLIENT```
* [napt66](https://github.com/mzweilin/napt66) ```CONFIG_FIRMWARE_INCLUDE_NAPT66```
* [softether-vpnserver](https://github.com/SoftEtherVPN/SoftEtherVPN_Stable) ```CONFIG_FIRMWARE_INCLUDE_SOFTETHERVPN_SERVER```
* [softether-vpnclient](https://github.com/SoftEtherVPN/SoftEtherVPN_Stable) ```CONFIG_FIRMWARE_INCLUDE_SOFTETHERVPN_CLIENT```
* [softether-vpncmd](https://github.com/SoftEtherVPN/SoftEtherVPN_Stable) ```CONFIG_FIRMWARE_INCLUDE_SOFTETHERVPN_CMD```
* [vlmcsd](https://github.com/hanwckf/vlmcsd) ```CONFIG_FIRMWARE_INCLUDE_VLMCSD```
* [ttyd](https://github.com/tsl0922/ttyd) ```CONFIG_FIRMWARE_INCLUDE_TTYD```
* [lrzsz](https://ohse.de/uwe/software/lrzsz.html) ```CONFIG_FIRMWARE_INCLUDE_LRZSZ```
* [htop](https://hisham.hm/htop/releases/) ```CONFIG_FIRMWARE_INCLUDE_HTOP```
* [nano](https://www.nano-editor.org/dist/) ```CONFIG_FIRMWARE_INCLUDE_NANO```
* [iperf3](https://github.com/esnet/iperf) ```CONFIG_FIRMWARE_INCLUDE_IPERF3```
* [dump1090](https://github.com/hanwckf/dump1090) ```CONFIG_FIRMWARE_INCLUDE_DUMP1090```
* [rtl-sdr](https://github.com/osmocom/rtl-sdr) ```CONFIG_FIRMWARE_INCLUDE_RTL_SDR```
* [samba3.6](https://gitlab.com/padavan-ng/padavan-ng/tree/master/trunk/user/samba36) ```CONFIG_FIRMWARE_INCLUDE_SMBD36```
* [mtr](https://github.com/traviscross/mtr) ```CONFIG_FIRMWARE_INCLUDE_MTR```
* [socat](http://www.dest-unreach.org/socat) ```CONFIG_FIRMWARE_INCLUDE_SOCAT```
* [srelay](https://socks-relay.sourceforge.io) ```CONFIG_FIRMWARE_INCLUDE_SRELAY```
* [3proxy](https://github.com/z3APA3A/3proxy) ```CONFIG_FIRMWARE_INCLUDE_3PROXY```
* [mentohust](https://github.com/hanwckf/mentohust-1) ```CONFIG_FIRMWARE_INCLUDE_MENTOHUST```
* [frpc](https://github.com/fatedier/frp) ```CONFIG_FIRMWARE_INCLUDE_FRPC```
* [frps](https://github.com/fatedier/frp) ```CONFIG_FIRMWARE_INCLUDE_FRPS```
* [tunsafe](https://github.com/TunSafe/TunSafe) ```CONFIG_FIRMWARE_INCLUDE_TUNSAFE```
* [wireguard-go](https://git.zx2c4.com/wireguard-go/) ```CONFIG_FIRMWARE_INCLUDE_WIREGUARD```
* [smartdns](https://github.com/pymumu/smartdns) ```CONFIG_FIRMWARE_INCLUDE_SMARTDNS```

## Supported Models: ##

```text
* PSG1208
* PSG1218
* 5K-W20 (USB)
* OYE-001 (USB)
* NEWIFI-MINI (USB)
* MI-MINI (USB)
* MI-3 (USB)
* MI-3C
* MI-4
* MI-R3G (USB)
* MI-R4A
* MI-R3P (USB)
* HC5661A
* HC5761A (USB)
* HC5861B
* 360P2 (USB)
* MI-NANO
* MZ-R13
* MZ-R13P
* RT-AC1200GU (USB)
* XY-C1 (USB)
* WR1200JS (USB)
* NEWIFI3 (USB)
* B70 (USB)
* A3004NS (USB)
* K2P
* K2P-USB (USB)
* JCG-836PRO (USB)
* JCG-AC860M (USB)
* DIR-882 (USB)
* DIR-878
* MR2600 (USB)
* WDR7300
* RM2100
* CR660x (CR6606, CR6608, CR6609)
* R2100
* JCG-Y2 (USB)
* E8820V2 (USB)
* ZTE_E8820S (USB)
* MSG1500 (USB)
* R6220 (USB)
* NETGEAR-CHJ (R6260, R6350, R6850, WAC124)
* NETGEAR-BZV (R6800, R6700-v2, R7200, Nighthawk AC2400)
```

***

### Compilation instructions ###

* Install dependencies

```shell
# Debian/Ubuntu
sudo apt update
sudo apt install unzip libtool-bin curl cmake gperf gawk flex bison nano xxd \
fakeroot kmod cpio git python3-docutils gettext automake autopoint \
texinfo build-essential help2man pkg-config zlib1g-dev libgmp3-dev \
libmpc-dev libmpfr-dev libncurses5-dev libltdl-dev wget libc-dev-bin -y

# Archlinux/Manjaro
sudo pacman -Syu --needed git base-devel cmake gperf ncurses libmpc \
        gmp python-docutils vim rpcsvc-proto fakeroot cpio help2man

# Alpine
sudo apk add make gcc g++ cpio curl wget nano xxd kmod \
pkgconfig rpcgen fakeroot ncurses bash patch \
bsd-compat-headers python2 python3 zlib-dev \
automake gettext gettext-dev autoconf bison \
flex coreutils cmake git libtool gawk sudo

# CentOS 7
sudo yum update
sudo yum groupinstall "Development Tools"
sudo yum install ncurses-* flex byacc bison zlib-* texinfo gmp-* mpfr-* gettext \
libtool* libmpc-* gettext-* python-docutils nano help2man fakeroot

# CentOS 8
sudo yum update
sudo yum groupinstall "Development Tools"
sudo yum install ncurses-* flex byacc bison zlib-* gmp-* mpfr-* gettext \
libtool* libmpc-* gettext-* nano fakeroot

# CentOS 8 Cannot install texinfo directly through yum，help2man，python-docutils. Please go to the official website to download the released installation package to compile and install
# Take texinfo as an example
# cd /usr/local/src
# sudo wget http://ftp.gnu.org/gnu/texinfo/texinfo-6.7.tar.gz
# sudo tar zxvf texinfo-6.7.tar.gz
# cd texinfo-6.7
# sudo ./configure
# sudo make
# sudo make install

```

* Clone the source code

```shell
#git clone --depth=1 https://e.coding.net/hanwckf/rt-n56u/padavan.git /opt/rt-n56u
git clone --depth=1 https://github.com/gustavo8000br/rt-n56u.git /opt/rt-n56u
```

* Preparing the toolchain

```shell
cd /opt/rt-n56u/toolchain-mipsel

# (Recommended) Download the precompiled toolchain using a script：
sh dl_toolchain.sh

# Alternatively, the toolchain can also be compiled from source, which will take some time：
./clean_toolchain
./build_toolchain

```

* (Optional) Modify the model configuration file

```shell
nano /opt/rt-n56u/trunk/configs/templates/PSG1218.config
```

* start compiling

```shell
cd /opt/rt-n56u/trunk
# For WSL environment, it is recommended to compile with sudo, or use fakeroot-tcp instead of fakeroot
fakeroot ./build_firmware_modify PSG1218
# The first parameter of the script is the routing model, in trunk/configs/templates/
# The compiled firmware is in trunk/images
# After the first compilation is completed, if you need to compile other firmware again, you need to execute the cleanup script：
./clear_tree
```

***

## See also ##

* [Lao Maozi Firmware Instructions](https://www.jianshu.com/p/cb51fb0fb2ac)
* [Padavan firmware compilation method](https://www.jianshu.com/p/6b8403cdea46)
