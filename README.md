# ARP Spoofer

This repository contains an ARP spoofing tool developed in Python. ARP spoofing is a type of attack where an attacker sends falsified ARP (Address Resolution Protocol) messages over a local network. This can allow the attacker to intercept, modify, or stop data intended for other hosts on the network.

## Features

- **ARP Spoofing**: Intercept and manipulate network traffic by sending spoofed ARP messages.
- **Network Scanning**: Discover hosts on the network to identify potential targets.
- **Easy to Use**: Simple command-line interface for executing ARP spoofing attacks.

## Prerequisites

- Python 3.x
- `pip` (Python package installer)
- Scapy (Python library for network manipulation)

## Setup Instructions

### 1. Clone the Repository

Clone this repository to your local machine:
```sh
git clone https://github.com/arifbinekram/ARP_Spoofer.git
cd ARP_Spoofer
```

### 2. Install Dependencies

Install the required Python libraries using `pip`:
```sh
pip install -r requirements.txt
```

### 3. Run the ARP Spoofer

Execute the ARP spoofer script with the necessary parameters. Example usage:
```sh
python arp_spoofer.py --target-ip TARGET_IP --gateway-ip GATEWAY_IP
```

Replace `TARGET_IP` with the IP address of the target machine and `GATEWAY_IP` with the IP address of the network gateway (router).

### 4. Stop the Attack

To stop the ARP spoofing attack and restore normal network operation, run the following:
```sh
python arp_spoofer.py --target-ip TARGET_IP --gateway-ip GATEWAY_IP --restore
```

## Usage

Here are some example commands and their descriptions:

- **Start ARP Spoofing**:
  ```sh
  python arp_spoofer.py --target-ip 192.168.1.5 --gateway-ip 192.168.1.1
  ```

- **Stop ARP Spoofing and Restore Network**:
  ```sh
  python arp_spoofer.py --target-ip 192.168.1.5 --gateway-ip 192.168.1.1 --restore
  ```

## Repository Structure

- `arp_spoofer.py`: The main script for performing ARP spoofing.
- `requirements.txt`: List of Python dependencies.
- `README.md`: This README file.

## Disclaimer

This project is intended for educational purposes only. Unauthorized use of these scripts is illegal and unethical. Always ensure you have explicit permission before deploying any form of ARP spoofing attack.


## Contributing

Contributions are welcome! Please open an issue or submit a pull request if you have any improvements or bug fixes.

---

**Note**: Always use such tools responsibly and within legal boundaries. This repository is meant to provide educational insights into network security for professionals and researchers. Misuse of these scripts can lead to serious legal consequences.
