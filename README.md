# 🏡 Smart Home Appliance Configuration

This repository provides Python and JavaScript (Node.js) scripts and usage instructions for controlling various smart home appliances, including:

- **Xiaomi Yeelight (Smart Bulb)**
- **Xiaomi Smart Fan**
- **Xiaomi Air Purifier**
- **Govee Air Humidifier**

<img src="/Fig13.jpg" style="float: left; margin-right: 20px; max-width: 200px;">



---

## 📦 Supported Devices & Libraries

| Device                   | Library Used                                                                 |
|--------------------------|------------------------------------------------------------------------------|
| Xiaomi Yeelight          | [`yeelight.io`](https://github.com/tonylin0826/yeelight.io)                 |
| Xiaomi Smart Fan         | [`python-miio`](https://github.com/rytilahti/python-miio)                   |
| Xiaomi Air Purifier      | [`python-miio`](https://github.com/rytilahti/python-miio)                   |
| Govee Air Humidifier     | [`homebridge-govee`](https://github.com/homebridge-plugins/homebridge-govee?tab=readme-ov-file) |

---

## 🚀 Getting Started

### 1. Installing the libraries with Python or Javascript required

Make sure to install the correct library for each smart home appliance before running any script.





### 2. Running the Scripts

You can run and test each smart home appliance using the provided scripts. These scripts include examples such as turning the devices on/off or setting them to specific values (e.g., brightness, speed, or mode).

Use the following command format to run the scripts:

#### Python Scripts
python script_name.py

python3 script_name.py


#### Node.js Scripts
node humidifier_control.js

## NOTE

### Yeelight app and MiHome app
You can also test the xiaomi smart home appliance using the mobile application below
[Yeelight](https://apps.apple.com/us/app/yeelight-classic/id977125608)
[Yeelight](https://apps.apple.com/us/app/xiaomi-home/id957323480)

### Obtaining tokens for Xiaomi Smart Fan and Smart Air Purifier (if not already existed in the script)

Getting Xiaomi Device Tokens
To use the Xiaomi Smart Fan and Air Purifier, you’ll need the device tokens.
Use this application to retrieve them:
[👉 Get_MiHome_devices_token](https://github.com/Maxmudjon/Get_MiHome_devices_token)

### Govee API key 
The api keys for the air humidifier is already presented in the script. If new API key is required, it can be obtained by requesting the API keys via the Govee mobile app.



