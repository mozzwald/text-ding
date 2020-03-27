# text-ding
PureOS SMS Alerts for PinePhones (led + sound)

Original source from https://github.com/pine-clover/text-ding/

steps to run:
1. ```sudo apt-get install vorbis-tools python3-pip python3-dbus```
2. ```mkdir ~/Projects & cd ~/Projects```
3. ```git clone git@github.com:mozzwald/text-ding.git```
4. ```cd text-ding/ & chmod +x main.py```
5. ```sudo cp main.py /usr/local/bin/text-ding```
6. ```mkdir -p ~/.config/autostart```
7. ```cp text-ding.desktop ~/.config/autostart```
8. Reboot
