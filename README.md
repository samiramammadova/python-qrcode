**Generate QR codes**.


A standard install uses pypng to generate PNG files and can also render QR codes directly to the console. A standard install is just:

-pip install pil-
For more image functionality, install qrcode with the pil dependency so that pillow is installed and can be used for generating images:

-pip install "qrcode[pil]"-

**What is a QR Code?**
A Quick Response code is a two-dimensional pictographic code used for its fast readability and comparatively large storage capacity. The code consists of black modules arranged in a square pattern on a white background. The information encoded can be made up of any kind of data (e.g., binary, alphanumeric, or Kanji symbols)

**Usage**

From the command line, use the installed qr script:

-qr "Some text" > test.png-
Or in Python, use the make shortcut function:
