<h1 align="center"> SNIGDHA OS SYSTEM INSTALLATION</h1>

>Example output from: /var/log/snigdhaos_vm_check.log

```bash
2024-11-20 15:00:00 - Starting Snigdha OS Virtual Machine Check...
2024-11-20 15:00:00 - Checking for Pacman lock (db.lck)...
2024-11-20 15:00:10 - Pacman is not ready yet. Trying in 10 seconds.
2024-11-20 15:00:20 - Removing Pacman db.lck!
2024-11-20 15:00:20 - You are on: kvm
2024-11-20 15:00:20 - Removing platform-specific packages and services...
2024-11-20 15:00:20 - [REMOVED] open-vm-tools
2024-11-20 15:00:20 - [REMOVED] xf86-video-vmware
2024-11-20 15:00:20 - [REMOVED] virtualbox-guest-utils
2024-11-20 15:00:20 - [REMOVED] virtualbox-guest-utils-nox
2024-11-20 15:00:20 - [SKIPPED] qemu-guest-agent is not installed.
2024-11-20 15:00:20 - [REMOVED] /etc/xdg/autostart/vmware-user.desktop
2024-11-20 15:00:20 - [SKIPPED] /etc/systemd/system/multi-user.target.wants/vmtoolsd.service does not exist.
2024-11-20 15:00:20 - [REMOVED] /usr/local/bin/snigdhaos-virtual-machine-check
2024-11-20 15:00:20 - [REMOVED] /etc/systemd/system/multi-user.target.wants/virtual-machine-check.service
2024-11-20 15:00:20 - Virtual machine check completed successfully.
```