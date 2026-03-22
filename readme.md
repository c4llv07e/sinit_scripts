Warning! A lot of customization is done by kernel patching and this init
code probably won't work on default linux kernel. Try in vm first and only
then install.

# Installation

Move or compile sinit into `/sbin/init` and place rc.init/rc.shutdown into
`/bin/` and add mounts for your system under namespace switch-case.

# Usefull

Also look at my [root repo](https://gitlab.com/c4llv07e/root_xdg_fhs) for
scripts and additional examples how to use this configuration. If you need,
I can publish my kernel patches, but they're just hardcoded hardware info,
so I don't know if they will help.
