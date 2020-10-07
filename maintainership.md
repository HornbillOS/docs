## HornbillOS

### How to apply?
***
You must fulfill the following criteria.

+ You must own the device. Blind and untested builds aren't allowed. Devices that have minimal hardware difference from yours are allowed to be maintained, as long as you maintain your own device too.
+ You must have a good knowledge of git.
+ You must create and maintain an unofficial build for at least 2 weeks, make sure that the build is stable for daily usage before applying. The context of stability may differ for different devices, so explain regarding any exceptions.
+ You must have your device sources available publicly with proper authorship for each commit.
+ You must show the real device sources being used.

Device Requirements

+ The device may have SELinux Enforcing to release builds.
+ The device must have complete hardware compatibility corresponding to the stock ROM, i.e. if IR blaster works on the stock ROM, it must work on PE. Only VoLTE is allowed to be ignored, so are NFC payment methods.
+ The device trees must have some required commits. You can check them at [this url](https://github.com/HornbillOS-Devices/required_commits).
+ The device must pass SafetyNet out of the box, without any 3rd part mods. If any device's stock build fingerprint works to bypass SafetyNet, those must take preference, even though that custom fingerprints (e.g. Pixels Build fingerprints) aren't restricted to be used.
+ The device may have encryption out of the box and we are in favor of it but not necessary.
+ The device must not include any unused overlays and packages. This includes, but is not limited to, packages not being built, packages that don't work, obsolete packages, placebo 'tweaks' or any packages that will include unnecessary and/or unwanted features.
+ If the device has Full Disk Encryption (a.k.a FDE) mustn't ship/build the Google Play System Updates/Updatable APEX, as the same only works on devices that have File-Base Encryption (FBE) with the device encrypted. The same is applicable for kernel 3.18 or devices with older kernel versions.

Maintainers Code of Conduct

+  All theirs device sources on HornbillOS-Devices organization. It goes without saying that these should be fully buildable. Using external repos for build releases aren't allowed, unless they're from LineageOS/TheMuppets and Sony Open Devices Project (SODP) organizations. Exceptions may be open if only it's a really big need.
+ Changelogs for each build. These MUST be user-friendly, simplifying the changes for the average user who aren't aware of things like Safetynet or color calibration, but would like to know what has changed since the last update.
+ Any Google applications that aren't available from ROM sources - except GoogleCamera is acceptable, but please ensure that you use a reliable source and that the device has proper support for them.

