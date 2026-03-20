# QRcode-reader
GUI of QRcode reader use zbar-tools and tkinter or tcl/tk<br>
これは、zbar-tools を GUIで簡単に利用できる様にしたアプリケーションです。
Tck/tkと、
Python3 tkinterで、実装しました。
前提プログラム
xclip python3 python3-tk (python3-tkinter) tk
sudo apt update
sudo apt install xclip python3-tk tk
使い方
sudo -i
で、root になって
qrcode1.png を /usr/share/icons
qrcode1.desktop を /usr/share/applications
ZBAR を /usr/local/bin (Tcl/tk版が使いたい場合は ZBAR.tkを ZBARにリネームしてください)
に入れます。
これだけで、起動メニューから選択できます。
なお、認識できるカメラが接続されていないと何もしません。
