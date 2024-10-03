# Network Honeypot Deployment

---

## Description

The **Network Honeypot Deployment** payload is designed to set up a basic SSH honeypot using **Cowrie** on a Linux machine. This payload is useful for educational purposes and security demonstrations, allowing you to attract and log unauthorized SSH login attempts. By using a honeypot, you can observe common attack patterns and gain insights into potential threats in a controlled environment.

## How it Works

1. The payload installs all necessary dependencies, including **Cowrie**, and sets up the honeypot environment.
2. It clones the Cowrie honeypot repository and sets up a virtual environment.
3. The honeypot is then started, simulating a vulnerable SSH server.
4. All SSH login attempts and interactions with the honeypot are logged.
5. The log file is copied to the Bash Bunny’s storage for analysis.

## Requirements

- Target: Linux machine with internet access
- Bash Bunny in HID and storage mode
- Cowrie honeypot installed via the payload

## Ethical Use Disclaimer

This payload is intended for ethical hacking, educational purposes, and security research only. Setting up honeypots in unauthorized environments or using them maliciously is illegal and unethical. Ensure you have the proper permissions before deploying this script.

## Liability Disclaimer

The author of this payload assumes no responsibility for any illegal or unethical use of the code. This payload is provided as-is, and it is the user's responsibility to ensure its use complies with all applicable laws and regulations.

## Usage

1. Insert the Bash Bunny into the target machine.
2. The payload will automatically install and configure the Cowrie honeypot.
3. Once deployed, the honeypot will begin logging all SSH interactions.
4. After capturing some data, the logs will be saved to `/cowrie_log.txt` on the Bash Bunny’s storage.
5. Eject the Bash Bunny and review the log file for analysis.
