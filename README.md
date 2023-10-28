# KlipperWrt

## Oct. 28th 2023: Status update

Due to life becoming incredibly busy for the past while, I have been unable to work on KlipperWRT-EX. I hope to continue once I have a proper build system set up for KlipperWRT - which is unfortunately waiting on the Proxmox Developers to release ZFS 2.2.0-pve.
~ Gramdalf

 ---------------------------------------------------------------------------------
 
 A guide to get _**Klipper**_ with _**fluidd**,_ _**Mainsail**_ or _**Duet-Web-Control**_ on OpenWrt embeded devices like the _Creality Wi-Fi Box_. Or (almost) any device that can run [OpenWRT](https://openwrt.org)
 
 ---------------------------------------------------------------------------------

> **Note**
> The old readme.md contains outdated information, so it has been moved off the main page. it can still be accessed [here](README.old.md).

The original [KlipperWRT](https://github.com/ihrapsa/KlipperWrt), while great, is not perfect. There is outdated information, unclear instructions, and a bunch of other things - such as no real support for any device other than the Creality Wi-Fi Box. KlipperWRT-EX intends to fix that.

KlipperWRT-EX revolves around a few core principles:
- UCI integration
- Reproducibility
- Simplicity
- Safety
More information on what this entails can be found [here](Docs/Principles.md)


--------------------------------------------------------------------------
### Credits:
* [ihrapsa](https://github.com/ihrapsa) for the initial work getting everything working
* the ideea: Hackaday.com - for the [article](https://hackaday.com/2020/12/28/teardown-creality-wifi-box) that set [ihrapsa](https://github.com/ihrapsa) on this journey to begin with
* the hard part: figgyc - for porting [OpenWrt](https://github.com/figgyc/openwrt/tree/wb01) to the Creality Wi-Fi Box
* the essentials: 
  - Kevin O'Connor - for [Klipper](https://github.com/KevinOConnor/klipper)
  - cadriel - for [fluidd](https://github.com/cadriel/fluidd)
  - mateyou - for [mainsail](https://github.com/meteyou/mainsail)  
  - Eric Callahan - for [Moonraker](https://github.com/Arksine/moonraker)
  - Stephan3 - for [dwc socket](https://github.com/Stephan3/dwc2-for-klipper-socket)
  - Duet3D - for [DuetWebControl](https://github.com/Duet3D/DuetWebControl)
* the fine tuning: andryblack - for the OpenWrt Klipper [service](https://github.com/andryblack/openwrt-build/tree/master/packages/klipper/files)
* the encouragement: [Tom Hensel](https://github.com/gretel)- for supporting [ihrapsa](https://github.com/ihrapsa) in this endeavour, which I have now continued

--------------------------------------------------------------------------
