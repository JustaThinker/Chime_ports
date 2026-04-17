# OEM Ports for Redmi 9T / POCO M3

Custom OEM firmware ports maintained by **Shyam aka ~ JustaThinker**.  
Primarily focused on **ColorOS (COS)**, **OxygenOS (OOS)**, and **MIUI** ports for **Redmi 9T (lime)** and **POCO M3 (citrus)**.

---

## 🔧 Project Vision
- Provide refined OEM ports adapted for these devices
- Maintain stability while keeping builds minimal and close to stock
- Ensure all essential hardware features (camera, audio, connectivity, sensors) remain functional
- Serve as a base for further customization and community development

---

## 📂 Repository Structure
- `/device` → Device‑specific configs and trees
- `/vendor` → Proprietary blobs adapted from OEM sources
- `/kernel` → Kernel sources or prebuilt images
- `/patches` → Applied fixes and optimizations

---

## 🚀 Flashing Guide
1. **Unlock bootloader** (official Xiaomi method).
2. **Install recovery** (TWRP/OrangeFox recommended).
3. **Download build** from [Releases](../../releases).
4. **Wipe**: system, data, cache (do not touch `internal storage` unless clean install).
5. **Flash zip** via recovery.
6. **Reboot** and set up your device.

---

## ⚠️ Disclaimer
- Provided *as‑is* with no guarantees.
- Flashing custom firmware carries risk — proceed only if you understand recovery methods.
- I am not responsible for bricked devices or data loss.

---

## 📝 Notes for Developers
- Ports are based on **COS, OOS, and MIUI OEM firmware dumps**, adapted for Redmi 9T / POCO M3.
- Contributions are welcome: submit pull requests with clear commit messages.
- Bug reports should include logs (`adb logcat`, `dmesg`) for effective debugging.

---

## 🤝 Credits
- **Nischay** — collaboration and testing support  
- **Mohan** — contributions and guidance  
- Xiaomi community for device trees and firmware references  
- ROM/porting community for shared knowledge  
- Testers and contributors who help refine builds

---

## 📧 Maintainer
**Shyam aka ~ JustaThinker**  
Reach out via GitHub Issues for queries or collaboration.
