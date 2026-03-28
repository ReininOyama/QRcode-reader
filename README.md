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
sudo dpkg -i qrcodereader_1.0.0.deb<br>
<br>
これだけで、起動メニューから選択できます。<br>
なお、認識できるカメラが接続されていないと何もしません。<br>
/usr/bin/ZBARを
ZBAR.th と交換すると Tcl/tk版になります。
