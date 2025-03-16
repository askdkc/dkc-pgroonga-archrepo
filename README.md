# Unofficial Personal Arch Repo for PGroonga

## How to use
Add this repo in your `/etc/pacman.conf` by following the steps below:

1. sudo open `/etc/pacman.conf`

``` bash
sudo vi /etc/pacman.conf
```

2. Add following line

``` vim
[dkc-pgroonga-archrepo]
SigLevel = Optional
Server = https://raw.githubusercontent.com/askdkc/$repo/refs/heads/main/$arch
```

3. Update pacman

``` bash
sudo pacman -Syyu
```

4. Install pgroonga

``` bash
sudo pacman -Sy pgroonga
```
