# PiRaTaS-GR Port Scanner 🏴‍☠️     

Welcome to the **PiRaTaS-GR Port Scanner** project! 🎉

This simple and fast port scanner allows you to check if ports are open or closed on any given server (either by domain name or IP address). 🌐

## Features 🚀

- **Port Scanning**: Scan ports from 1 to 65535 on any server! 💻🔌
- **Multithreaded**: Faster scanning with the use of multiple threads! ⚡
- **Friendly Interface**: Get clear and easy-to-read results! ✅
- **Colorful Output**: It uses colors to make the output more fun and easier to understand! 🎨

## How to Use 📚

1. **Clone the repository**:
    ```bash
    git clone https://github.com/PiRaTaS-GR/Port-Scanner.git
    ```
    
2. **Setup Environment**:
    ```bash
   cd Port-Scanner && python3 -m venv myenv && source myenv/bin/activate && pip install pyfiglet && pip install colorama
    ```

3. **Run the script**:
    ```bash
    python start.py
    ```

4. **Follow the prompts**: The script will ask you to enter the domain or IP you want to check, and it will return the status of each port.

    - Input domain or IP, e.g. `example.com` or `192.168.1.1`.
    - The script will then check all the ports (1-65535) for open ports.

5. **Want to scan again?**: After the scan, the program will ask if you want to check another domain/IP. Type **yes** to continue, or **no** to exit.

## Example Output 📊

```text
Please enter the domain or IP to check (e.g. example.com or 192.168.1.1): example.com
Checking ports for server example.com...
Port 22 is open
Port 80 is open
Port 443 is open

Do you want to check another domain/IP? (yes/no): yes
