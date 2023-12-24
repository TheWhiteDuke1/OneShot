Данный скрипт нужен для TERMUX
Данный код был взят и руссифицирован у drygdryg.

Вручную
Установка требований

1) pkg install -y root-repo
2) pkg install -y git tsu python wpa-supplicant pixiewps iw openssl

Получение OneShot

git clone --depth 1 https://github.com/TheWhiteDuke1/OneShot OneShot

Запуск

sudo python OneShot/oneshot.py -i wlan0 --iface-down -K
