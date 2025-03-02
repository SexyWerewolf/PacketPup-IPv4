# Python DDoS Attack

A Python-based DDoS attack for educational purposes, designed to work with IPv4 addresses. It simulates sending UDP packets to a target IP and port, with features like attack duration, and progress tracking. **For educational use only.**

---

## Features

- Sends UDP packets to a target IPv4 address and port.
- Configurable attack duration and loop settings.
- Displays a progress bar during the attack.
- Saves configuration for easy reuse.

---

## Installation

1. **Clone the repository:**

```bash
git clone https://github.com/SexyWerewolf/PacketPup-IPv4.git
```

2. **Navigate to the project folder:**
```bash
cd PacketPup-IPv4
```

3. **Install the required dependencies:**
```bash
pip install -r requirements.txt
```


## Usage
1. **Run the script:**
```bash
python PacketPup-IPv4
```

2. **Configure attack parameters:**

``The script will prompt you for the target IP address, port, and attack time in seconds.``

``You can also choose whether the attack should loop.``


## Configuration

The script supports a configuration file (`config.ini`) for storing IP, port, attack time, and loop settings. The script will automatically load the last used configuration or prompt the user for new input.

Example of `config.ini`:

```ini
[Settings]
ip = 192.168.1.1
port = 8080
loop = true
time = 10.0
