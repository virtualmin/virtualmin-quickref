| Files and Directories |                              |
|:----------------------|:-----------------------------|
| Webmin Config         | `/etc/webmin`                |
| Virtualmin Config     | `/etc/webmin/virtual-server` |

| Logs            |                                           |
|:----------------|:------------------------------------------|
| Webmin Logs     | `/var/webmin`                             |
| Domain Web Logs | `/var/log/virtualmin`                     |
| Mail Log        | `/var/log/maillog` or `/var/log/mail.log` |

| Ports           |       |
|:----------------|:------|
| Webmin          | 10000 |
| Virtualmin      | 10000 |
| Usermin Webmail | 20000 |

| Software Updates |                                   |
|:-----------------|:----------------------------------|
| Debian/Ubuntu    | `apt-get update; apt-get upgrade` |
| RHEL/CentOS      | `yum update`                      |

| Services                                 |                                       |
|:-----------------------------------------|:--------------------------------------|
| Webmin Start/Stop/Status                 | `systemctl start/stop/status webmin`  |
| Apache Start/Stop/Status (CentOS/RH)     | `systemctl start/stop/status httpd`   |
| Apache Start/Stop/Status (Debian/Ubuntu) | `systemctl start/stop/status apache2` |

| Virtualmin CLI |                             |
|:---------------|:----------------------------|
| List Commands  | `virtualmin help`           |
| Command Help   | `virtualmin help <command>` |

| Virtualmin Misc     |                                                   |
|:--------------------|:--------------------------------------------------|
| Change License      | `virtualmin change-license --serial SN --key KEY` |
| Change Password     | `virtualmin change-password username`             |
| Check Configuration | `virtualmin check-config`                         |

| Backup and Restore |                                       |
|:-------------------|:--------------------------------------|
| Backup Domain      | `virtualmin backup-domain [options]`  |
| Restore Domain     | `virtualmin restore-domain [options]` |
| List Backup Keys   | `virtualmin list-backup-keys`         |

| Virtualmin Domains |                                           |
|:-------------------|:------------------------------------------|
| Create Domain      | `virtualmin create-domain [options]`      |
| Delete Domain      | `virtualmin delete-domain --domain name`  |
| Disable Domain     | `virtualmin disable-domain --domain name` |
| Enable Domain      | `virtualmin enable-domain --domain name`  |
| List Domains       | `virtualmin list-domains`                 |

| Mail and FTP |                                      |
|:-------------|:-------------------------------------|
| Create User  | `virtualmin create-user [options]    |
| Delete User  | `virtualmin delete-user --user name` |
| List Users   | `virtualmin list-users`              |
