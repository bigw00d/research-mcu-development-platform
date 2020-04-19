# mbed

## mbed CLI

1. install
    1. do web site procedure(https://qiita.com/toyowata/items/86a312158187cafe3f7d)
    1. install 
```txt
C:\WorkSpace\mbedos2-cli-ps2controller-host>mbed config root .
C:\WorkSpace\mbedos2-cli-ps2controller-host>mbed compile -m LPC1768 -t GCC_ARM
C:\WorkSpace\mbedos2-cli-ps2controller-host>copy BUILD\LPC1768\GCC_ARM\mbedos2-cli-ps2controller-host.bin D:\
```

1. build & upload project
```txt
C:\WorkSpace\mbedos2-cli-ps2controller-host>mbed config root .
C:\WorkSpace\mbedos2-cli-ps2controller-host>mbed compile -m LPC1768 -t GCC_ARM
C:\WorkSpace\mbedos2-cli-ps2controller-host>copy BUILD\LPC1768\GCC_ARM\mbedos2-cli-ps2controller-host.bin D:\
```
or
```txt
C:\WorkSpace\mbedos2-cli-ps2controller-host>mbed config root .
C:\WorkSpace\mbed-repo\mbedos2-cli-ps2controller-host>mbed compile -c -m LPC1768 -t GCC_ARM
C:\WorkSpace\mbed-repo\mbedos2-cli-ps2controller-host>copy BUILD\LPC1768\GCC_ARM\mbedos2-cli-ps2controller-host.bin D:\
```
* '-c' is clean build option
* You only need to do  'mbed config root .' the first time you use.

1. import library

    1. go to library web site(ex.https://os.mbed.com/users/okini3939/code/PS_PAD/)
    1. select 'import with CLI' and copy repository URL command
    1. execute command

### Related Links
1. [mbed CLI with VSCode](https://os.mbed.com/users/ytsuboi/notebook/ja-setup-mbed-cli-on-windows/)
1. [Mbed OS 2のサポートがいつ終わっても良いようにローカル環境を構築する方法【改訂版】](https://qiita.com/toyowata/items/86a312158187cafe3f7d)
## WEB IDE
1.  mbed([url1](https://os.mbed.com/platforms/mbed-LPC1768/))

