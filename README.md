# AR Smart IR

**AR Smart IR** is a custom Home Assistant integration for controlling **infrared devices** such as **TVs, air conditioners, projectors, fans, lights, and media players** using supported IR transmitters.

Built for modern Home Assistant systems, **AR Smart IR** removes the need for old-style YAML setup and allows device configuration directly through the **Integrations UI**.

---

## ✨ Features

- 🌡️ Control **climate devices** such as air conditioners
- 📺 Control **media players** such as TVs and projectors
- 🌀 Control **fans**
- 💡 Control **lights**
- ⚙️ Works with modern **config flow**
- 🖥️ Setup through **Home Assistant UI**
- 🚫 **No YAML configuration required**
- ⚡ Improved compatibility with newer Home Assistant versions

---

## 🚀 Supported Controller Methods

AR Smart IR supports infrared control through compatible Home Assistant services and controller platforms, including:

- **ESPHome IR transmitters**
- **MQTT publish services**
- **Broadlink IR controllers**
- **Xiaomi IR Remote**
- Other compatible **Home Assistant remote platforms**

---

## 🆕 What Makes AR Smart IR Different?

AR Smart IR is designed to modernize legacy IR control in Home Assistant.

### Key improvements:
- ✅ **No more `configuration.yaml` setup required**
- ✅ Device setup is done inside **Settings → Devices & Services**
- ✅ Uses **Config Flow** for easier installation
- ✅ Cleaner structure for modern Home Assistant versions
- ✅ Improved async handling and updated compatibility
- ✅ Easier for users who want UI-based setup instead of manual config

---

## 📦 Installation

### Manual Installation

Copy the integration into your Home Assistant `custom_components` directory:

```text
config/
└── custom_components/
    └── ar_smart_ir/
        ├── __init__.py
        ├── manifest.json
        ├── config_flow.py
        ├── climate.py
        ├── fan.py
        ├── light.py
        ├── media_player.py
        ├── controller.py
        ├── services.yaml
        ├── strings.json
        ├── translations/
        │   └── en.json
        └── icons.json

Then:

Restart Home Assistant

Go to Settings → Devices & Services

Click Add Integration

Search for AR Smart IR

Complete setup directly in the UI

🧩 Integration Setup

Unlike older IR integrations, AR Smart IR no longer depends on YAML configuration.

Everything is handled through the Integrations UI, making setup faster and easier.

Setup path:

Settings → Devices & Services → Add Integration → AR Smart IR

This means:

no manual YAML entries

no restarting just to change settings

easier setup for normal users and installers

cleaner long-term maintenance

🏠 Supported Device Types

AR Smart IR currently supports:

Climate devices

Media players

Fans

Lights

Device control is handled using IR command codes transmitted through supported Home Assistant controller services.
