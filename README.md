
Epson LQ 300 Printer Driver for Linux (Dot Matrix Printer)
---------------------------------------------------------

1. Download the ppd file from the below link
   
[Epson-Dot_Matrix-epson.ppd](https://raw.githubusercontent.com/purvalpatel/Epson-LQ-300-driver-linux/9a679dc35524706fea6f6047a9177295bc0b93ff/Epson-Dot_Matrix-epson.ppd)


[epson-en-eplq300.ppd.gz](https://raw.githubusercontent.com/purvalpatel/Epson-LQ-300-driver-linux/9a679dc35524706fea6f6047a9177295bc0b93ff/epson-en-eplq300.ppd.gz)
2. copy both files at below location
```
cp  epson-en-eplq300.ppd.gz /usr/share/cups/model/
cp Epson-Dot_Matrix-epson.ppd /usr/share/cups/model/
```

3. change the permission of the driver files
```
chmod 0777 /usr/share/cups/model/Epson*

chmod 0777 /usr/share/cups/model/epson*
```
4. set dpi into the printer settings
182 DPI (in capital)
   
Epson TM-T81,TM-T82 Series Printer Drivers for linux
----------------------------------------------------
1. Download the driver from the below link:

[epson-tm-t81-t82.tar.gz](https://github.com/purvalpatel/Epson-LQ-300-driver-linux/raw/ce00f9e2a99f2f8f3b9a00a343185e7154288f79/epson-tm-t81-t82.tar.gz)

2. Extract the downloaded file

3. Navigate to the location where zip file is extracted

4. `bash ./install.sh`

Now check the driver list of Epson

Epson Thermal Printers  Drivers are now available.

RP-3200 STAR Printer Driver For ubuntu
-------------------------------------
Download driver from below link
and extract the zip file

[RP-3200-STAR-Linux-Driver.zip](https://github.com/purvalpatel/Epson-LQ-300-driver-linux/raw/5d03bbd67ad58ff16f20f5745c37f9ecbd1db5f0/RP-3200-STAR-Linux-Driver.zip)

Epson L380 Printer Driver for Ubuntu
------------------------------------
Download driver from here:
[epson-inkjet-printer-201601w_1.0.0-1lsb3.2_i386.deb](https://raw.githubusercontent.com/purvalpatel/Epson-LQ-300-driver-linux/ae007ed5ef5df855068028ba215d47d451a55e37/epson-inkjet-printer-201601w_1.0.0-1lsb3.2_i386.deb)

Want to support ?

[By me coffee.](https://coff.ee/purval)
