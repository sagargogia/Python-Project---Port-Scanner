# Python-Project---Port-Scanner

## Overview
This Python script is a basic port scanner that scans a range of ports on a specified IP address to identify open ports.

## Requirements
- Python 3.x
- Socket module (comes with Python)

## Usage
1. Clone or download the repository.
2. Open a terminal or command prompt.
3. Navigate to the directory where the script is located.
4. Run the script:

    ```bash
    python port_scanner.py
    ```

    or for Python 3:

    ```bash
    python3 port_scanner.py
    ```

5. Enter the target IP address when prompted.

## Script Explanation
The script defines a function `scan_ports` that takes the target IP address, start port, and end port as parameters. It then iterates through the specified port range, attempts to connect to each port, and records the open ports.

The script uses a timeout of 1 second for each connection attempt to speed up the scanning process. After scanning, it prints the list of open ports on the specified IP address.

## Example
```bash
Enter the target IP address: 192.168.1.1
Open ports on 192.168.1.1: [22, 80, 443]
