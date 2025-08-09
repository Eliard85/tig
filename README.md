# tig

sudo wget -O /etc/systemd/system/tig.service https://github.com/Eliard85/tig/raw/refs/heads/main/tig.service && sudo nano /etc/systemd/system/tig.service

sudo systemctl enable tig.service

./pool_tig_launch_*.sh --cpu_workers 0 - для запуска без cpu
