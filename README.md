# Ansible-Role: acr-ansible-mate-autostart

AIT-CyberRange: Customizes ubuntu mate desktop environment.


## Requirements

- Debian or Ubuntu 

## Role Variables

**Example config:**

```yaml
client_autostart_absent_list:
  - snap-userd-autostart.desktop
  - indicator-application.desktop
  - mate-power-manager.desktop
  - mate-screensaver.desktop
  - nm-applet.desktop
  - onboard-autostart.desktop
  - org.gnome.SettingsDaemon.Wacom.desktop
  - update-notifier.desktop
  - org.gnome.SettingsDaemon.ScreensaverProxy.desktop
  - org.gnome.SettingsDaemon.Smartcard.desktop
  - print-applet.desktop
  - geoclue-demo-agent.desktop
```

## Example Playbook

```yaml
- hosts: localhost
  roles:
    - acr-ansible-mate-autostart
```

## License

GPL-3.0

## Author

- Lenhard Reuter