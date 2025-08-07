# tig

sudo wget -O /etc/systemd/system/tig.service https://github.com/Eliard85/tig/raw/refs/heads/main/tig.service

sudo systemctl enable tig.service

./pool* --cpu_workers 0 для запуска без cpu
