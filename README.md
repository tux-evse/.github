# .github
## Tux-Evse Rust based charger software for ISO15118-2x and OCPP-2.x

Tux-Evse aims at providing a highly cybersecure EV charger reference implementation independent of hardware boards.

* It mostly uses RUST for hight level logic and C for level interface with the OS. As must as possible we tried to reduce RUST dependencies by strongly limiting crate.io usage.
* It relies on AFB-V4 micro service architecture. Nevertheless afb-binding code is kept independent of service logic, in case someone would prefer an other micro-service framework.
* Cybersecurity is built-in and leverages redpesk Linux distribution for mandatory access control and application live cycle management as well as Cynagora for API access control.
* Tux-EvSe rely on others existing evse OSS projects as Everest/Pionix or OCPP/Codelabs
* Outside of explicitly noted this project is publish under Apache-V2 license.