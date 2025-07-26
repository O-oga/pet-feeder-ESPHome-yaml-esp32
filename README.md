Here’s an updated and visually appealing README for your project, reflecting that the pet eats by pressing a button (not by schedule):

---

# 🐾 Pet Feeder ESPHome YAML for ESP32

A ready-to-use YAML configuration to build a smart pet feeder with an ESP32 board, powered by [ESPHome](https://esphome.io/) and fully compatible with [Home Assistant](https://www.home-assistant.io/).

---

## 🚀 Features

- **Self-Feeding:** Your pet can independently trigger feeding by pressing a physical button on the feeder.
- **Manual Feeding:** Instantly trigger feedings via Home Assistant or a physical button.
- **Portion Control:** Dispense a set amount of food with each feeding.
- **Status Monitoring:** Track feeding events, errors, and device status.
- **Sensor Integration:** Support for weight sensors, limit switches, and more (configurable).
- **Notifications:** Get alerts for successful feedings or errors.

_All features and hardware options are defined in the YAML file. Customize to fit your feeder!_

---

## 🛠️ Getting Started

### 1. **Hardware Needed**
- ESP32 development board
- Motor/servo for food dispensing
- Feeding button for pet-initiated feeding
- [Printed case](https://www.printables.com/model/872397-pet-feeder)

### 2. **Setup Steps**
1. Clone or download this repository.
2. Install [ESPHome](https://esphome.io/) in your HomeAssistant.
3. Edit the YAML file for your hardware and preferences.
4. Flash the ESP32 using ESPHome.
5. Add your device to Home Assistant for full control.

---

## 📄 Configuration

All logic and customization live in the main YAML file.  
**Review and adjust it to match your hardware and automation needs.**

---

## 🤝 Integration with Home Assistant

- Native ESPHome device integration.
- Control, monitor, and automate your feeder from the Home Assistant dashboard.
- Easily add notifications or use with other smart home automations.

---

## 📷 Example
![feeder](https://github.com/user-attachments/assets/b7a7f3d0-c273-4a74-bec3-d9de756c9fb9)

<img width="2416" height="1036" alt="image" src="https://github.com/user-attachments/assets/dcccd240-9042-4991-b540-ac1b83e3f1d3" />


---

## 📚 Resources

- [ESPHome Docs](https://esphome.io/)
- [Home Assistant Docs](https://www.home-assistant.io/integrations/esphome/)

---

## 📝 License

This project is licensed under the MIT License.

---

Feel free to copy-paste this into your `README.md`!  
Let me know if you want to add YAML code snippets, wiring diagrams, or any other details.
