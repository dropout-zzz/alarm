systemctl enable serial-getty@ttyGS0

timedatectl set-time 'yyyy-MM-dd hh:mm:ss'
systemctl enable fake-hwclock fake-hwclock-save.timer
systemctl start fake-hwclock
