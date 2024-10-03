## tux-evse: Rust software stack for electric vehicules & chargers

 * targeting [redpesk-os](https://redpesk.bzh/welcome/home) a CentOS-stream derivated plateform.
 * nevertheless provided cargo/cmake are standard should work on any serious Linux plateform.
   
### Main components

This project Rust modules:

 * ISO15118-2/Din stack [iso15118-encoder-rs](https://github.com/tux-evse/iso15118-encoders-rs)
 * ISO15118 simulator [iso15118-simulator-rs](https://github.com/tux-evse/iso15118-simulator-rs)
 * SLAC/ISO15118-3 binding [slack-binding-rs](https://github.com/tux-evse/slac-binding-rs)
 * OCPP binding [ocpp-binding-rs]([https://github.com/tux-evse/iso15118-simulator-rs](https://github.com/tux-evse/ocpp-binding-rs))
 * TCP/TLS/SDP [iso15118-network-rs](https://github.com/tux-evse/iso15118-network-rs)
 * Graphic LVGL Rust api [lvgl-rclib-rs](https://github.com/tux-evse/lvgl-rclib-rs)
 * OpenAMP rpmsg/protobus [ti-am62x-binding-rs](https://github.com/tux-evse/ti-am62x-binding-rs)
 * Linky binding [linky-binding-rs](https://github.com/tux-evse/linky-binding-rs)

 Tux-EVSE default configuration [evse-project-manager-config](https://github.com/tux-evse/evse-project-manager-config) 
 
### How to use our packages into our community redpesk stack

1. Connect you on [redpesk community](https://community-app.redpesk.bzh) (Github or Gitlab login account required)
2. Import your BSP project ([BeaglePlay](https://download.redpesk.bzh/community/iot-charger/iot-tux-evse-beagleplay.zip) or [Raspberry Pi 4b](https://download.redpesk.bzh/community/iot-charger/iot-tux-evse-raspberry-pi-4b.zip)) or create your own! (New Project -> Import - more details [here](https://docs.redpesk.bzh/docs/en/master/redpesk-factory/projects-management/01-export-import.html#webui-1))
3. Import the Tux-EVSE project from [here](https://download.redpesk.bzh/community/iot-charger/iot-tux-evse-community.zip)

You can now modify packages, add patches or create new package. 

For the image generation, please refer to the [documentation](https://docs.redpesk.bzh/docs/en/master/redpesk-factory/images-management/01-create-an-image.html#creation-of-a-basic-redpesk-os-image).
