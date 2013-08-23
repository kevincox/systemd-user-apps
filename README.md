# Systemd User Application Configss

A collection of systemd services for desktop users.

Install them to one of:
```
/etc/systemd/user/
/usr/lib/systemd/user/
~/.config/systemd/user/
```

Then `systemctl --user enable ${service}.service`.
