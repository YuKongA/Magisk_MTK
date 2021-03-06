## 2021.2.11 Magisk v21.4_YuK

### YuK

- Remove AvB verify when using MediaTek devices
- Add Platform printing when using MediaTek devices

### v21.4

- [MagiskSU] Fix `su -c` behavior that broke many root apps
- [General] Properly handle read/write over sockets (the `broken pipe` issue)

### v21.3

- [MagiskInit] Avoid mounting `f2fs` userdata as it may result in kernel crashes. This shall fix a lot of bootloops
- [MagiskBoot] Fix a minor header checksum bug for `DHTB` header and ASUS `blob` image formats
- [MagiskHide] Allowing hiding isolated processes if the mount namespace is separated

### [Full Changelog](https://topjohnwu.github.io/Magisk/changes.html)

### 夹带私货

- [coolapk](http://www.coolapk.com/u/680367)
- [余空の杂货间](https://yukongya.herokuapp.com)
