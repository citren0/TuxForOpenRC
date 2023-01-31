# TuxForOpenRC
OpenRC init script to add tux to the boot screen, with color. Like in gentoo linux, but without a framebuffer driver and as ascii art.

Move this file to your /etc/init.d/ directory for OpenRC users.

\# chown root:root /etc/init.d/aalogo
\# chmod 755 /etc/init.d/aalogo
\# rc-update add aalogo boot

Adding to the boot runlevel will ensure the penguins show up on screen even when elogind spawns the login prompt.
Please set the permissions correctly, I will not be responsible for you getting pwned from improper file permissions.
