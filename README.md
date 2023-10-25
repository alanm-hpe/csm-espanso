# csm-espanso
A collection of frequently used CSM text expansion shortcuts.

# Installation
Follow the espanso package installation for your OS:
https://espanso.org/install/

Install this package with:
```
espanso install csm --git git@github.com:alanm-hpe/csm-espanso.git --external
```

Once installed, this package should be visible in the espanso package list:
```
$ espanso package list
Installed packages:

- csm - version: 0.1.0 (git: git@github.com:alanm-hpe/csm-espanso.git)
```

You may need to restart espanso:
```
espanso restart
```


# Requires
The CSM espanso text expansion requires the commands `cray` and `sat`.

On any CSM Management node, these commands should already be present.

If you'd like to install `cray` and `sat` locally to your OS, consider using:
https://github.com/Cray-HPE/superinit

Alternatively, follow installation instructions for `cray` and `sat` in their respective repos:
https://github.com/Cray-HPE/craycli
https://github.com/Cray-HPE/sat
