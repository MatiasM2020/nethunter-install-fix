Install Termux

https://f-droid.org/packages/com.termux/

https://github.com/termux/termux-app/releases

Download latest termun version, app_v0.118.0

Open Termux
run:

apt update

apt upgrade yes to all

Create storage

termux-setup-storage

apt install wget

wget -O install-nethunter-termux https://offs.ec/2MceZWr

chmod +x install-nethunter-termux

./install-nethunter-termux

run twice if error

![IMG_20241229_152827_997](https://github.com/user-attachments/assets/729407c7-d8d6-4d35-9909-d9cb73c838f0)

Fix this error with this commands

mkdir chroot

mv kali-arm64/* chroot/

./install-nethunter-termux


