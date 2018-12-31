# Installation

```bash
wget https://raw.github.com/hectornguyen/autossh/master/autossh.sh -O /usr/local/bin/autossh
```
# Usage

This usage is as same as `ssh` command but I suggest you use SSH aliases instead of IP, for example

```bash
autossh root@prod-server
```
Or you can enter to interactive mode by just use it without any paramters

```bash
autossh
```
It will ask you to enter SSH Username and SSH IP/Aliases.

Reference to SSH aliases, please take a look to [this guide](https://coderwall.com/p/dou7uw/multiple-aliases-on-every-entry-of-ssh-s-config-file).

