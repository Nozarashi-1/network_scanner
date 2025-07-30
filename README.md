🌐 Network Scanner
A simple Python-based ARP network scanner that identifies active devices on a local network by their IP and MAC addresses.

📌 Description:
This tool sends ARP requests across a user-specified IP range and collects responses from connected devices.

	⚠️ Note: This script requires root privileges and works only on Linux systems with Python and Scapy installed.

🚀 Features:

    Scans a full IP range using ARP requests

    Displays a clean list of IP and MAC addresses

    Fast and lightweight — uses raw packets via Scapy

🛠️ Requirements:

    Python 3.x

    scapy (pip install scapy)

    Linux OS

    Root privileges

🔧 Installation:

    git clone https://github.com/Nozarashi-1/network-scanner.git

    cd network-scanner

    pip install scapy

⚙️ Usage:

Run the script with sudo and specify the target IP or subnet: 

    sudo python scanner.py -t <target IP or IP range>

Example:

    sudo python scanner.py -t 192.168.1.0/24

To view help info:   

    python scanner.py --help

    
