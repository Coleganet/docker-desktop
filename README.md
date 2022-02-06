# docker-desktop
Install docker desktop ubuntu 18.04


curl https://desktop-stage.docker.com/linux/main/amd64/74134/docker-desktop.deb --output docker-desktop.deb


sudo apt install ./docker-desktop.deb

systemctl --user start docker-desktop


systemctl --user enable docker-desktop


journalctl --user --unit=docker-desktop
