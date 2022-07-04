## About the application
<p style="font-size:18px">This is a Web Application writed with HTML/CSS & JS with backend Python<br><br>
You can generate a lot of QR Codes with this simple way you can add your text<br>
and after you clicking the button the image will apear.
<br>


## Getting Started
- Clone the repo and cd into the directory
```sh
$ git clone git@github.com:georgebak2182/qr-code-generator.git
$ cd qr-code-generator
```

- Install eel, pyqrcode, and pyinstaller

```sh
$ pip install eel pyqrcode pyinstaller pypng
```

- Run the app

```sh
$ python QRCode.py
```
## Packaging the app to .exe extension
python -m eel QRCode.py web --noconsole --onefile --icon barcode.ico<br>
<B>Check <a href="https://github.com/samuelhwilliams/Eel">EEL</a> how to pack the application if this way isn't working</b>
