#TERMUX-SETUP

apt update && apt upgrade -y

pkg install git

pkg install python

rm -rf TERMUX-SETUP

git clone https://github.com/NAFIS-124/TERMUX-SETUP.git

cd TERMUX-SETUP

python3 BSET.py
