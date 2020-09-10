***Athom devices come with modified Tasmota which is not entirely compatible with regular releases. To have full compatibility upgrade to main release version***

Before upgrading set your device to module `Generic (19)` (yes, it is 19 in this build) to avoid clicking relays, flashing lights or button resets after upgrade. Perform upgrade to release version using file upload method with [tasmota.bin.gz](http://ota.tasmota.com/tasmota/release/tasmota.bin.gz) or [tasmota-lite.bin.gz](http://ota.tasmota.com/tasmota/release/tasmota-lite.bin.gz) or with OTAUrl. **DO NOT use tasmota-minimal.bin!**. 

None of the setting will be retained after the upgrade. You will have to search for Tasmota AP and redo the Wi-Fi and MQTT configuration. Once you've upgraded do `Reset 6` to erase flash and apply the template!

If you use OTAUrl upgrade with precompiled binaries there is a chance of soft bricking your device. In most cases it is possible to restore it using [Power Cycle Recovery](https://tasmota.github.io/docs/Device-Recovery/#fast-power-cycle-device-recovery) or, if that fails, with serial flash. 