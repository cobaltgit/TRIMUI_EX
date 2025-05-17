# PortMaster Bootstrap Gluon

This gluon bootstraps PortMaster for Quark v2.0.0 "Fission" and is based on kloptops' [TRIMUI_EX](https://github.com/kloptops/TRIMUI_EX) bootstrapper, with any unneeded components removed.

**This gluon is not compatible with the TrimUI Smart. Please use this with the TrimUI Smart Pro or TrimUI Brick.**

## Install

To install, drag and drop `Quark_System_PortMaster.tar.zst` into `SDCARD:/System/archives`, then insert your microSD card into your Smart Pro or Brick and boot.

The version of PortMaster that is installed with the bootstrapper is out of date, but with your device connected to WiFi you will be able to update straight after launching PortMaster for the first time.

Port data will be stored in `SDCARD:/Data/ports` and launch scripts will be stored in `SDCARD:/Roms/PORTS64` and bind mounted over `SDCARD:/Roms/PORTS` on a 64-bit device. This way, ports can be kept separate between the Smart (32-bit) and Smart Pro/Brick (64-bit) architectures.
