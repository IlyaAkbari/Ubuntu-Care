sudo nano /usr/local/bin/optimize-ubuntu.sh

#!/bin/bash
apt autoremove -y
apt autoclean -y
rm -rf /var/cache/apt/archives/*.deb
sync
sysctl -w vm.drop_caches=3
