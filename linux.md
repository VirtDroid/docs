With this you may run Manjaro, Ubuntu Kali Linux, Fedora, Void and much more with only three apps

## Starting with dependencies
You will need [F-Droid](https://f-droid.org/) to install Termux and run the VMs
### Installing dependencies
- You need Termux from [F-Droid](https://f-droid.org/en/packages/com.termux/)
- You need [andronix](https://andronix.app/)
- You will need a VNC viewer (I suggest [RealVNC viewer](https://www.realvnc.com/en/connect/download/viewer/android/))

## Starting
To get started open Termux and wait for it to instll, then type `pkg update`
Open andronix and choose the distro you prefer, then click Desktop Envoirnement and choose one. Finally click "Open Termux".
Paste the content andronix copied and wait for it to install.
You will be "booted" into the distro you've chosen. Type `vncserver-start`, open RealVNC and connect to `localhost:1`. You will be in a Linux Envoirnement.
If you close termux, to start your distro type `./start-<distro>.sh`
<p></p>
You can install almost every Linux software, even an AUR helper on arch and derivates. To get docs, click [here](/docs/aur)
