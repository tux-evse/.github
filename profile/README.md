## tux-evse: Rust software stack for electric vehicules & chargers

This project Rust modules:

 * ISO15118-2/Din stack [iso15118-encoder-rs](https://github.com/tux-evse/iso15118-encoders-rs)
 * ISO15118 simulator [iso15118-simulator-rs](https://github.com/tux-evse/iso15118-simulator-rs)
 * SLAC/ISO15118-3 binding [slack-binding-rs](https://github.com/tux-evse/slac-binding-rs)
 * OCPP binding [ocpp-binding-rs)[https://github.com/tux-evse/iso15118-simulator-rs]
 * TCP/TLS/SDP iso15118 network stack [iso15118-network-rs](https://github.com/tux-evse/iso15118-network-rs)
 * Graphic LVGL Rust api [lvgl-rclib-rs)[https://github.com/tux-evse/lvgl-rclib-rs]
 * OpenAMP rpmsg/protobus [ti-am62x-binding-rs](https://github.com/tux-evse/ti-am62x-binding-rs)
 * Linky binding [linky-binding-rs](https://github.com/tux-evse/linky-binding-rs)

 Tux-evse ship a default configuation [evse-project-manager-config](https://github.com/tux-evse/evse-project-manager-config) 
 
 * targeting (redpesk-factory)[https://redpesk.bzh/welcome/home] a CentOS-stream derivated plateform.
 * nevertheless provided cargo/cmake are standard should work on any serious Linux plateform.
