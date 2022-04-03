### How to build this app

Build step:
* Install jar2app
* Build for mac application

**Install jar2app:**

``` shell
$ git clone https://github.com/Jorl17/jar2app
$ cd jar2app
$ chmod +x install.sh uninstall.sh
$ sudo ./install.sh /usr/local/bin
```
**Build for mac application:**

``` shell
$ jar2app ns-usbloader-5.2.jar -n "NS-USBloader" -x universalJavaApplicationStub -r /Library/Java/JavaVirtualMachines/openjdk.jdk -i logo.icns -v 5.2
$ jar2app ns-usbloader-5.2-legacy.jar -n "NS-USBloader" -x universalJavaApplicationStub -r /Library/Java/JavaVirtualMachines/openjdk.jdk -i logo.icns -v 5.2
```
