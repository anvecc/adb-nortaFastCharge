# 🌩️ NortaFastCharge 🌩️

Fast charging optimization module for Poco X3 Pro (vayu).

## 📋 Requirements

- Device: Poco X3 Pro (vayu)
- Root: KernelSU / KernelSU Next / Magisk
- Android: 10-16

## ⚡ Features

- Force enable fast charge mode
- Remove charging current restrictions
- Optimize input current limit
- Configurable charge level via `config.sh`

## 📦 Installation

1. Download the latest zip
2. Open KSU/Magisk Manager
3. Install from storage → select zip
4. Reboot

## ⚙️ Configuration

Default charge level is set to **5000 mA**. If you want to change it, open `config.sh` in ZArchiver (whatever file editor.) before installing and edit `CHARGE_LEVEL`:

```sh
# Options: 2670, 3000, 3500, 4000, 4500, 5000, 5500
CHARGE_LEVEL=5000  # Change this value
```

Higher value = faster charging, more heat.

## ⚠️ Warning

- Use at your own risk
- Do not exceed charger's rated current
- Monitor battery temperature regularly
- Tested on ArrowOS + Anymore Kernel

## 👨‍💻 Credits

- Inspired by FCGreen by NTH
- Nodes research & testing: Norta
- Made for vayu community

## 📬 Contact

- Telegram: @iamnorta
- Channel: t.me/iamnorta

## 📥 Download

Get the latest release from the [Releases](https://github.com/anvecc/adb-nortaFastCharge/releases) page.

