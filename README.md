# csm-espanso
A collection of frequently used CSM text expansion shortcuts.

# Why should I use this?
Have you been using sshrc or wrapper scripts to automate frequent CSM tasks?

Do you forget `cray` commands regularly?

Are you tired of typing "--format json"?

This espanso library offers the following quality of life improvements:
* The text expansions are available everywhere.
* No more special configs or scripts to copy from one environment to another.
* See the actual commands being executed.
* Commands are present in history and are reverse searchable.
* Benefit from the shortcuts provided by the community.
* :boom: Supercharge your work by pairing `csm-espanso` with [superinit](https://github.com/Cray-HPE/superinit) :boom:

# Installation
Follow the espanso package installation for your OS:
https://espanso.org/install/

Once `espanso` is installed, add this package with:
```
espanso install csm --git git@github.com:alanm-hpe/csm-espanso.git --external
```

Once added, this package should be visible in the espanso package list:
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
