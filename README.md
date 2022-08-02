sudo apt install git libusb-1.0-0-dev pkg-config
git clone --depth=1 https://github.com/raspberrypi/usbboot
cd usbboot
make
sudo ./rpiboot
