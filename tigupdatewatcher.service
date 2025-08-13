[Unit]
Description=tig_update_watcher
After=network.target

[Service]
ExecStart=/bin/bash -c '/home/user/tig_pool_main/tig_update_watcher.sh'
Restart=always
RestartSec=5
User=user
WorkingDirectory=/home/user/tig_pool_main/
Environment="PATH=/usr/local/bin:/usr/bin:/bin"

[Install]
WantedBy=multi-user.target
