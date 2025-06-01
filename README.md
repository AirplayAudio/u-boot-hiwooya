#u-boot-mt7688
##uboot for HI-WOOYA V1.0.3
***
#How to use
* 1.make menuconfig
* 2.select MT7628 board
* 3.make clean;make

#Note
* note:compile need java such as 1.7.0_79
yum install java-1.8.0-openjdk -y
or
apt-get install java-1.8.0-openjdk -y

*Please modify the file path of buildroot-gcc342 in the Makefile and config.in to match your own path.
/root/uboot-76x8/u-boot-hiwooya/buildroot-gcc342/bin

#update list
* change bps to 115200,fix gpio39,40,41,42 low when startup
* add all gpio test,just press 'WPS' button with more than 7 seconds at power on
* web failsafe update mode,just press 'WPS' button with 2 to 7 seconds at power on
* web failsafe IP is 192.168.1.111
* DDR2 can be 64MB or 128MB,just select 512Mbit or 1024Mbit in menuconfig
***
* QQ:317312379
* mail:317312379@qq.com
***
## Official website:www.hi-wooya.com
