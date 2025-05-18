# 🏡 Smart Home Appliance Configuration

This repository provides Python and JavaScript (Node.js) scripts and usage instructions for controlling various smart home appliances, including:

- **Xiaomi Yeelight (Smart Bulb)**
- **Xiaomi Smart Fan**
- **Xiaomi Air Purifier**
- **Govee Air Humidifier**

The project enables integration and automation of smart home devices using open-source libraries and local network protocols (LAN mode), offering a customizable and privacy-respecting alternative to vendor apps.

---

## 📦 Supported Devices

| Device                   | Protocol/Method       | Library Used                        |
|--------------------------|------------------------|--------------------------------------|
| Xiaomi Yeelight          | LAN protocol (TCP)     | [`python-yeelight`](https://github.com/rytilahti/python-yeelight) |
| Xiaomi Smart Fan         | miIO protocol          | [`python-miio`](https://github.com/rytilahti/python-miio)         |
| Xiaomi Air Purifier      | miIO protocol          | [`python-miio`](https://github.com/rytilahti/python-miio)         |
| Govee Air Humidifier     | Bluetooth Low Energy   | [`govee-led-python`](https://github.com/LaggAt/python-govee-api) or custom BLE library |

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/smart-home-appliance-config.git
cd smart-home-appliance-config
