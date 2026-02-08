## Part 1: Home Assistant + ESPresense (Room-Level Presence & Automations)

In this video, we take a deep dive into ESPresense with Home Assistant for accurate room-level presence detection.
We cover ESP32 setup, BLE device enrollment, MQTT verification, and real-world automations such as conditional visibility and notifications when leaving home with your wallet still behind — including fixes for common issues along the way.

## Watch the video here:
▶️ [Home Assistant + ESPresense (Room-Level Presence & Automations)](https://youtu.be/iEi1qsz4o9I)

## 📖 Written Articles
- **[Enabling BLE Transmission (Android & iOS)](https://github.com/LazyTechGeek/HomeAssistant-ESPresense/blob/main/Enabling-BLE-Transmission-(Android_%26_iOS).pdf)**

## ⚙️ MQTT Room Sensors
- **[MQTT Room Sensors (Split)](https://github.com/LazyTechGeek/HomeAssistant-ESPresense/blob/main/mqtt-room-sensors-split.yaml)**
- **[MQTT Room Sensors (Non-Split)](https://github.com/LazyTechGeek/HomeAssistant-ESPresense/blob/main/mqtt-room-sensors-non-split.yaml)**

## ⚙️ Automation examples used in this video
- **[notify when wallet left at home](https://github.com/LazyTechGeek/HomeAssistant-ESPresense/blob/main/automation_notify-when-wallet-left-at-home.yaml)**
- **[enable guest mode when tile home](https://github.com/LazyTechGeek/HomeAssistant-ESPresense/blob/main/automation_enable-guest-mode-when-tile-home.yaml)**
- **[disable guest mode when tile away](https://github.com/LazyTechGeek/HomeAssistant-ESPresense/blob/main/automation_disable-guest-mode-when-tile-away.yaml)**


---

## Part 2: Home Assistant + ESPresense Companion (Calibration & Floor Design)

In this video, we focus on the ESPresense Companion Add-on for Home Assistant, covering floor design, adding nodes and devices, and applying optimisation and calibration to improve accuracy in your setup

## Watch the video here:
▶️ [Home Assistant + ESPresense Companion (Calibration & Floor Design)](https://youtu.be/BVqqHakNuE4)

## ⚙️ Config YAML used in this video
 💡 These files are examples only. Rename the one you want to `config.yaml` inside your ESPresense directory before using it.
- **[config-clean-baseline.yaml – saved at 11:42 (after cleaning up the default YAML)](https://github.com/LazyTechGeek/HomeAssistant-ESPresense/blob/main/espresense-companion/config-clean-baseline.yaml)**
- **[config-final-example.yaml – final working example](https://github.com/LazyTechGeek/HomeAssistant-ESPresense/blob/main/espresense-companion/config-final-example.yaml)**
