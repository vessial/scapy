How to Install Scapy into your iDevice?

first Jailbreak your iOS device(iPhone/iPad)

install Python into your device.

you can download python into your device from here http://cydia.radare.org/debs/python_2.7.3-3_iphoneos-arm.deb

then ssh to your device : dpkg install python_2.7.3-3_iphoneos-arm.deb

copy scapy and Crypto directory, dnet.pyx pcap.py scapy-2.1.-py2.7.egg-info to 

/usr/lib/python2.7/site-packages this directory.

copy lib-dynload/_pcapmodule.so
     lib-dynload/dnet.so
     
into /usr/lib/python2.7/lib-dynload directory

enjoy it.

vessial
