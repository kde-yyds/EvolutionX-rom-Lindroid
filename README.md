# Custom ROMs built for Redmi K60/POCO F5 Pro (mondrian) with Lindroid
## Source
You can find All patches and build guide [here](https://github.com/kde-yyds/device_xiaomi_mondrian-patch).
## Notes
Selinux is enforcing by default on my builds. It causes a dead touch on Lindroid. Disable it temporarily by running `setenforce 0` as root.  
If you don't want to flash it, you can extract `odm,product,system,system_ext,vendor` images and compress them into a zip to install with DSU Sideloader
