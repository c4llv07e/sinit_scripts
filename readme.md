Warning! A lot of customization is done by kernel patching and this init
code probably won't work on default linux kernel. Try in vm first and only
then install.

# Installation

Move or compile sinit into `/sbin/init` and place rc.init/rc.shutdown into
`/bin/` and add mounts for your system under namespace switch-case.
