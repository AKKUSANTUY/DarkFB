#DarkFB Termux v3.4.0

pkg install git python2 coreutils nano curl -y

pip2 install --upgrade pip

git clone https://github.com/AKKUSANTUY/DarkFB

cd DarkFB

pip2 install -r requirements.txt

python2 DarkFB.py

Catatan:

Jikan ingin menambahkan list password edit dengan perintah:
nano password.bin
