# QRcode-reader
GUI of QRcode reader use zbar-tools and tkinter or tcl/tk<br><br>
これは、zbar-tools を GUIで簡単に利用できる様にしたアプリケーションです。<br>
Tck/tkと、<br>
Python3 tkinterで、実装しました。<br>
前提プログラム<br>
xclip python3 python3-tk (python3-tkinter) tk<br>
sudo apt update<br>
sudo apt install xclip python3-tk tk<br>
使い方<br>
sudo -i<br>
で、root になって<br>
qrcode1.png を /usr/share/icons<br>
qrcode1.desktop を /usr/share/applications<br>
ZBAR を /usr/local/bin (Tcl/tk版が使いたい場合は ZBAR.tkを ZBARにリネームしてください)<br>
に入れます。<br>
これだけで、起動メニューから選択できます。<br>
なお、認識できるカメラが接続されていないと何もしません。<br>
