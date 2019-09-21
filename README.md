# LineageOS 17 releases for galaxy a5, all SM-A500 variants

<b>This project is currently discontinued, which means that it will no longer get updates</b>

This repo contains lineageos 17 builds for all Galaxy A5 SM-A500 variants!

<b>How to install lineageos 17</b>:

Flash twrp recovery <br />
Wipe system, data, cache, and dalvik if you are using a different rom or android version (for example lineage 16.0), otherwise, if you are just updating lineageos 17.0 you won't have to do that. <br />
Flash lineageos 17.0 zip <br />
Flash your variant's RIL fix zip otherwise RIL (the ability to make calls, send sms, connect through cellular data) will probably not work <br />
Optional but recommended: download and flash gapps <br />
Reboot


<b>IMPORTANT!</b>

As written above you will have to flash RIL-fix zip to make RIL working. <br />
If your variant is SM-A500FU, you will not have to flash any RIL-fix zip! <br />
RIL zip contains device-specific libsec-ril.so and libsec-ril-dsds.so, if the device supports dual sim. <br />
In addition it also contains a script to change build.prop device-name props from SM-A500FU ones to your variant's ones. <br />
Here are the RIL-fix zips. Make sure you install the one corresponding to your variant!

Temporary main RIL fix which must be flahsed by all non-FU variants (MM to LP ril blobs): <br />
[ril fix common.zip](https://drive.google.com/open?id=1ecewhS0uUGGGOQk_qhTwsqeEm2LoLLvW)

Device-specific ril fix to be flashed after the common one

[ril fix A500F.zip](https://drive.google.com/open?id=1RaZ4vT7PLi3rLVpvddfOvVe_6DJfozzp) (SM-A500F) <br />
[ril fix A500F1.zip](https://drive.google.com/open?id=1vBhADKvWqmc7luzikOv28qpkCxjJT8wE) (SM-A500F1) <br />
[ril fix A500G.zip](https://drive.google.com/open?id=1z_kvcgDMHHF1SSUkvw4FrXe83_B3dYZ3) (SM-A500G) <br />
[ril fix A500H.zip](https://drive.google.com/open?id=1IFVjE-MUEunNaO3GmpMXO61E4Z7whjAs) (SM-A500H) <br />
[ril fix A500K.zip](https://drive.google.com/open?id=15xa8ZI5rx5KI1x7nv_4WO9fDX_hyyJj3) (SM-A500K) <br />
[ril fix A500L.zip](https://drive.google.com/open?id=11YTjG0_9-R0OwNETODna5R6bfUCpdVZP) (SM-A500L) <br />
[ril fix A500M.zip](https://drive.google.com/open?id=1oZ4U7bej-SKlimKPbiVpAvDjnryeQDXB) (SM-A500M) <br />
[ril fix A500S.zip](https://drive.google.com/open?id=1AkZASnubX40OGNL9a-OzIK_N-YjjGg2-) (SM-A500S) <br />
[ril fix A500W.zip](https://drive.google.com/open?id=1RaWEFDj1IzUMiEYu_txaXS0aumyLl3Fk) (SM-A500W) <br />
[ril fix A500Y.zip](https://drive.google.com/open?id=1CcwHwCCaQkvU6p_H098dJUfdMriSKO6H) (SM-A500Y) <br />
[ril fix A500YZ.zip](https://drive.google.com/open?id=14LN5gjp9rIXXw6jXeElhMiVrNROPS8g8) (SM-A500YZ)


LineageOS 17.0 releases can be found at https://github.com/DeadSquirrel01/lineage-17_a5_releases/releases


<b>Donations</b> <br />
If you like my work and want to buy me a coffe, you can send a donation to my paypal address: https://www.paypal.me/marcomarcaccini <br />


Changelog can be found at: https://github.com/DeadSquirrel01/lineage-17_a5_releases/blob/master/changelog.txt


<b>ROM support</b> <br />
If you have any questions not related to ROM issues, or want to talk about this ROM or A5 modding, you can join http://t.me/galaxya5mod Telegram group
