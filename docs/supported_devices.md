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
| 🟩 | ✔️ | 🇸 | 🔌 | 🛜 | **TL** | `_TZ3000_iwhuhzdo` <br> `TS0003` | [HSlice KEP 3-gang (iwhuhzdo)](https://www.zigbee2mqtt.io/devices/TS0003.html) |   |   | Confirmed by HSlice | 
| 🟩 | ✔️ | 🇸 | 🔌 | 🛜 | **TL** | `_TZ3000_u4kojtqz` <br> `TS0002` | [HSlice KEP 2-gang (u4kojtqz)](https://www.zigbee2mqtt.io/devices/TS0002.html) |   |   | Confirmed by HSlice | 
| 🟩 | ✔️ | 🇸 | 🔌 | 🛜 | **TL** | `_TZ3000_ubrvwoxv` <br> `TS0001` | [HSlice KEP 1-gang (ubrvwoxv)](https://www.zigbee2mqtt.io/devices/TS0001.html) |   |   | Confirmed by HSlice | 
| 🟩 | ✔️ | 🇸 | 🔌 | 🛜 | **TL** | `_TZ3000_zcbpj2t6` <br> `TS0003` | [HSlice TA 3-gang (zcbpj2t6)](https://www.zigbee2mqtt.io/devices/TS0003.html) |   |   | Confirmed by HSlice | 
| 🟩 | ✔️ | 🇸 | 🔌 | 🛜 | **TL** | `_TZ3000_ehgouyvu` <br> `TS0001` | [HSlice LS 1-gang (ehgouyvu)](https://www.zigbee2mqtt.io/devices/TS0001.html) |   |   | Confirmed by HSlice | 
| 🟩 | ✔️ | 🇸 | 🔌 | 🛜 | **TL** | `_TZ3000_b7s7xsow` <br> `TS0001` | [HSlice LS 1-gang (b7s7xsow)](https://www.zigbee2mqtt.io/devices/TS0001.html) |   |   | Confirmed by HSlice | 
| 🟩 | ✔️ | 🇸 | 🔌 | 🛜 | **TL** | `_TZ3000_aa5t61rh` <br> `TS0002` | [HSlice LS 2-gang (aa5t61rh)](https://www.zigbee2mqtt.io/devices/TS0002.html) |   |   | Confirmed by HSlice | 
| 🟩 | ✔️ | 🇸 | 🔌 | 🛜 | **TL** | `_TZ3000_rhkfbfcv` <br> `TS0003` | [HSlice LS 3-gang (rhkfbfcv)](https://www.zigbee2mqtt.io/devices/TS0003.html) |   |   | Confirmed by HSlice | 
| 🟩 | ✔️ | 🇸 | 🔌 | 🛜 | **TL** | `_TZ3000_vit9k2nb` <br> `TS0004` | [HSlice LS 4-gang (vit9k2nb)](https://www.zigbee2mqtt.io/devices/TS0004.html) |   |   | Confirmed by HSlice | 

Data from [`device_db.yaml`](/device_db.yaml)
