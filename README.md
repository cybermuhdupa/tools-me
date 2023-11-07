# tools-me : Extended tools in https://github.com/0xarun/s1mr3c

git clone https://github.com/cybermuhdupa/tools-me/

cd tools-me

mv * /usr/local/bin/

cd ../s1mr3c/

mv s1mr3c /usr/local/bin

chmod +x *


-------=
apt-get install sqlmap nmap -y
----wordlist

git clone https://github.com/v0re/dirb.git

mkdir -p /usr/share/wordlists/dirb

mv dirb/wordlists/* /usr/share/wordlists/dirb/

rm -rf dirb

HOW USER : bash s1mr3c target.com
---
