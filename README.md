# Unofficial Amazon Workspaces Client Snap

The one provided by Nightmayr-snaps is outdated (potentially abandoned?), and I was tired of running it in a full Ubuntu 24.04 virtual machine so here we are. This is my first Snap and I got to learn a lot about the process and certain Ubuntu changes (i.e. the move away from Debian `lsb_release`).

This repository and work is in no way endorsed, sponsored, or supported by Amazon. Since they only formally support Ubuntu on Linux it would be nice if they released their own official Snap since clearly they have a complex build process.

## Building and local install

```
snapcraft
sudo snap install ./workspacesclient-*.snap --dangerous
```
