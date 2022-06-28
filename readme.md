# Barcode Server
A barcode server for Barcode Client Server android app.

You can use it for
- Customize Software
- MS Excel
- Google Spreadsheet
- MS Word
- Any PC software for input barcode data.


Watch: [Video Tutorial](https://youtu.be/l2qS5Zagm-I)


Server App (v2.0.1)            |  Mobile App
:-------------------------:|:-------------------------:
for Windows [Download exe](https://github.com/haruncpi/barcode-server/releases/download/v2.0.1/BarcodeServer-2.0.1.zip) <br> for Linux [Download deb](https://github.com/haruncpi/barcode-server/releases/download/v2.0.1/barcodeserver_2.0.1_amd64.deb) <br> Mac - [Intel version](https://github.com/haruncpi/barcode-server/releases/download/v2.0.1/barcodeserver-2.0.1-mac-intel.zip) <br> Mac - [M1 version](https://github.com/haruncpi/barcode-server/releases/download/v2.0.1/barcodeserver-2.0.1-mac-m1.zip) <br> [Follow Guide for MacOs](#important-for-mac-os)| [Download from PlayStore](https://play.google.com/store/apps/details?id=com.learn24bd.barcode)
![](barcode-server.png) |  ![](app-preview.png)


### Important for Mac OS
Run these command after install the app into `Applications` folder.

```
sudo xattr -rd com.apple.quarantine Applications/barcodeserver.app
```

```
sudo codesign --force --deep --sign - Applications/barcodeserver.app
```

### Command Snippet

Program            |  Use command |  Comment
:------------------:|:------------:|:----------
Google Spreadsheet | `Barcode Delay:100ms Down` |
MS Excel | `Barcode Enter` |



1- https://www.mediafire.com/file/2xl606cb3rioegu/Barcode_Client_Server_1.2.9_apkcombo.com.apk/file

2- https://www.mediafire.com/file/tedtn38uh2d1w9m/BarcodeServer-2.0.1.zip/file

