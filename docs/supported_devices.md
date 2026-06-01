# Supported devices

Support new devices: [contribute/porting.md](/docs/contribute/porting.md)  

### Quick-picks
- **modules:** AVATTO, Aubess, iHseno
- **switches:** Moes 1-3gang (any design, except Star Feather)

### Careful with
- generic 1-gang modules - might not support OTA conversion
- BSEED switches - too many variants (can't know which you'll receive)

### Legend

| Symbol | Meaning  |                    |                     |                |                |           |          |
| :----: | -------- | ------------------ | ------------------- | -------------- | -------------- | --------- | -------- |
|   🚧️   | Status   | 🟩️ Fully supported | 🟨️ Mostly supported | 🟧️ In progress | 🟥️ Unsupported |           |          |
|   📦️   | Build    | ✔️ Available       | ❌️ Unavailable      |                |                |           |          |
|   💡️   | Category | 🇲️ Module          | 🇸️ Switch           | 🇴️ Outlet      | 🇵 Plug        | 🇷️ Remote | 🇧️ Board | 
|   ⚡️   | Power    | 🔌️ Mains           | 🔋️ Battery          | 🔱️ USB         |                |           |          |
|   📲️   | Install  | 🛜️ Wireless        | ➿️ By wire          | ❓️ Unknown     |                |           |          |
|   🏭️   | MCU      | `TL` Telink        | `SL` Silicon Labs   | `NXP` NXP      |                |           |          |
|   🅰   | Variant  | 🅰                  | 🅱                  | 🅲             | 🅳              | 🅴        | 🅵        |

<!-------------------------------------------------------------------
  `supported.md` is generated. 
  
  Do not edit it directly! Instead, edit:
  - `device_db.yaml`             - add or edit devices
  - `supported_devices.md.jinja` - update the template
  - `make_supported_devices.py`  - update generation script

  Generate with: `make tools/update_supported_devices`
-------------------------------------------------------------------->

> [!IMPORTANT]  
> Identify your device by **Zigbee Manufacturer** and linked threads/stores!  
> *Z2M pages are sometimes generic.*

### Device list

| 🚧 | 📦 | 💡 | ⚡️ | 📲 |  🏭  | Zb&nbsp;Manufacturer <br> Zb&nbsp;Model | Name <br> Z2M&nbsp;page&nbsp;🔗 | Store | Threads | Status |
| -- | -- | -- | -- | -- | :--: | :-------------------------------------- | :------------------------------ | ----: | ------: | :----- |
| 🟨 | ✔️ | 🇸 | 🔌 | 🛜 | **TL** | `_TZ3000_b7s7xsow` <br> `TS0001` | [Lonsonho 1 Gang Switch (b7s7xsow)](https://www.zigbee2mqtt.io/devices/TS0001_switch_1_gang.html) |   |   | PCB A3M04-10/LH1F02. Same PCB as ehgouyvu, pinout assumed same - needs verification. | 
| 🟩 | ✔️ | 🇸 | 🔌 | 🛜 | **TL** | `_TZ3000_ehgouyvu` <br> `TS0001` | [Lonsonho X701A 1 Gang Switch](https://www.zigbee2mqtt.io/devices/X701A.html) |   |   | PCB A3M04-10/LH1F02. Pinout confirmed by user testing. | 
| 🟧 | ✔️ | 🇸 | 🔌 | 🛜 | **TL** | `_TZ3000_aa5t61rh` <br> `TS0002` | [Lonsonho X702A 2 Gang Switch](https://www.zigbee2mqtt.io/devices/X702A.html) |   |   | PCB A3M04-10/LH1F02. Gang 1 pinout assumed from ehgouyvu. Gang 2 pins unconfirmed - needs verification. | 
| 🟧 | ✔️ | 🇸 | 🔌 | 🛜 | **TL** | `_TZ3000_rhkfbfcv` <br> `TS0003` | [Lonsonho X703A 3 Gang Switch](https://www.zigbee2mqtt.io/devices/X703A.html) |   |   | PCB A3M04-10/LH1F02. Gang 1 pinout assumed from ehgouyvu. Gang 2+3 pins unconfirmed - needs verification. | 
| 🟧 | ✔️ | 🇸 | 🔌 | 🛜 | **TL** | `_TZ3000_vit9k2nb` <br> `TS0004` | [Tuya 4 Gang Switch (vit9k2nb)](https://www.zigbee2mqtt.io/devices/TS0004_switch_4_gang.html) |   |   | PCB A3M04-10/LH1F02. Gang 1 pinout assumed from ehgouyvu. Gang 2+3+4 pins unconfirmed - needs verification. | 

Data from [`device_db.yaml`](/device_db.yaml)
