Laptop
======

Laptop is a script to set up an macOS laptop for web and mobile development.

It can be run multiple times on the same machine safely.
It installs, upgrades, or skips packages
based on what is already installed on the machine.

Install
-------

Download the script:

```sh
sh -c "$(curl -fsSL https://raw.githubusercontent.com/andrewstucki/laptop/master/laptop)" 2>&1 | tee ~/install.log
```

Optionally, review the log:

```sh
less ~/install.log
```
