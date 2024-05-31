# Cinnamon Desktop On Github Codespace
This configuration will install a Cinnamon desktop enviornment and automatically opens a VNC connection. To access VNC. open PORTS tab, open forwarded address, click on `vnc.html` and enter your password

The default VNC password is just `password`. You can it using `vncpasswd` in Terminal. You don't need to worry about weak password because the vnc ports are not public by default, accessing the ports requires your Github account to be logged. This makes it a lot secure

The default keyboard layout is English (US). You can change it in Cinnamon settings

To run Windows app, use Wine: https://wiki.winehq.org/Ubuntu

To unlock better machine types, file a ticket to Github: https://support.github.com/contact?tags=rr-codespaces%2Ccat_codespaces

Using desktop enviornment on Codespace is generally allowed since Microsoft themself provided a documentation setting up a Fluxbox based desktop and installing a browser; https://github.com/devcontainers/features/tree/main/src/desktop-lite, but we will use Cinnamon instead. You don't need to worry about getting banned as long as you don't abuse the service and don't violate Github ToS

# Limitations & bugs
- No hardware acceleration because Codespace does not have a GPU
- Terminal won't open. May work if you use Ubuntu 20.04

# Screenshots

