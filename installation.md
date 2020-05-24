# Installation

Login into your machine via SSH and type this command, if you are in with a sudoer user (not root) run this command in the bash:

``` bash
wget -O setup.sh https://raw.githubusercontent.com/sculptor-devops/installer/master/bin/setup.sh | sudo setup.sh
```

If you are in with the root user the command need to bue run in alternate mode:

``` bash
wget -O setup.sh https://raw.githubusercontent.com/sculptor-devops/installer/master/bin/setup.sh | setup.sh
```

This operation will take several minutes to finish, at the end you will recive all credentias. Save those data in a secure place. Seee advance usage to find additiona options for installer customizations.

::: warning
All operations have to be done on a new clean machine, **DO NOT RUN this installer** on already installer machine.
:::

# Troubleshooting
In case of an error all data and details are dumped to the installer.log file, is situated in the user home but the system will tell you where it is. I case of problems or bugs you can open an [issue](https://github.com/sculptor-devops/installer/issues) on github.

# Requirements

| OS        | Version           | Provider  |
|-------------|-------------|-----|
| Ubuntu      | 18.04 | Amazon EC2, Digital Ocean, ScaleWay |
| Ubuntu      | 20.04 | In developement |

# Services

| Service  | Ubuntu 18.4 | Ubuntu 20.04 |
|-------------|-------------|-------------|
| MySql  | 5.7.x | TBD |
| Nginx | 1.x | TBD |
| Redis | 2.x | TBD |
| Supervisor | 1.x | TBD |
