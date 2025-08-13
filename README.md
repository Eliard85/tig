# tig

sudo wget -O /etc/systemd/system/tig.service https://github.com/Eliard85/tig/raw/refs/heads/main/tig.service && sudo nano /etc/systemd/system/tig.service

sudo systemctl enable tig.service


sudo wget -O /etc/systemd/system/tigupdatewatcher.service https://github.com/Eliard85/tig/raw/refs/heads/main/tigupdatewatcher.service

sudo systemctl enable tigupdatewatcher.service

./pool_tig_launch_*.sh --cpu_workers 0 - для запуска без cpu
