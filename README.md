# fastbootlin

sudo systemctl disable bluetooth cups ModemManager && sudo sed -i 's/GRUB_TIMEOUT=[0-9]\+/GRUB_TIMEOUT=0/' /etc/default/grub && sudo update-grub && sudo systemctl mask sleep.target suspend.target hibernate.target hybrid-sleep.target && sudo systemctl enable systemd-bootchart
