# Network Engineering: Automated MAC Address Spoofer

## 📝 Description
This network utilities project automates hardware address obfuscation inside Linux operating environments. By interacting directly with system infrastructure controls via Python's native `subprocess` engine, the script unlinks designated network interfaces, rewrites their localized MAC address registry fields, and hot-swaps the adapter profile to facilitate privacy validation or hardware access bypass auditing.

## 🛠️ Features
* **Subprocess System Hooks:** Directly orchestrates underlying Linux system level network utility strings (`ifconfig`/`ip`).
* **Hardware Address Customization:** Forces immediate hardware mapping shifts to simulate arbitrary client identities.
* **Non-Destructive Execution Flow:** Safely drops network interface frames before making configuration adjustments to prevent kernel memory conflicts.

## 🚀 How to Run It

### Prerequisites
* Python 3.x installed.
* Linux distribution environment (e.g., Parrot OS, Ubuntu).
* System root administrative privileges to alter active device states.

### Execution
1. Clone the repository:
   ```bash
   git clone [https://github.com/YOUR-USERNAME/mac-address-spoofer.git](https://github.com/YOUR-USERNAME/mac-address-spoofer.git)
