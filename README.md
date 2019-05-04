# ambed-debian-installer
This is a simple install script to install AMBED, a piece of software that when combined with hardware AMBE vocoder chips and another piece of software, XLXD, can transcode digital voice modes. This script simply runs through the official install instructions found at:
https://github.com/LX3JL/xlxd/blob/master/ambed/readme
### To Install:
1. Have a Debian 9.x computer ready and up to date with a 64bit CPU architecture.
2. Plug the AMBE vocoder chips into the server.
3. 
```sh
git clone https://github.com/n5amd/ambed-debian-installer
cd ambed-debian-installer
./ambe-debian-installer
```
4. Reboot after installation is complete.

### To interact with ambed after installation:
```sh
systemctl start|stop|status|restart ambed
```
 - Installs to /ambed
 - Logs are via systemctl status


**The other parts to this install, if you need it can be found at:**

https://github.com/n5amd/Multi-Reflector-Installer

**For more information, please visit:**

https://n5amd.com/digital-radio-how-tos/build-digital-voice-transcoding-server/
