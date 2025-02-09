Overview

This project is a Python-based port scanner designed to identify open ports on specified target IP addresses or hostnames. It assists in network analysis and security assessments by checking the connectivity of specified ports.
Features

    Target Specification: Scan a single IP address or multiple targets separated by commas.
    Port Range Selection: Define the range of ports to scan, from 1 up to 65535.
    Threaded Scanning: Utilizes multithreading to enhance scanning speed and efficiency.
    Verbose Output: Option to display all scanned ports and their statuses or only the open ones.

Requirements:

    Python 3.x: Ensure Python 3 is installed on your system.

    Socket Library: This is included with Python by default.

    IP Address Parsing: The IPy library allows flexible IP address and subnet management.

Project Structure:

    port_scanner.py: The main script responsible for scanning ports.

Contributing:

Contributions are welcome! Please fork the repository and submit a pull request with any improvements or fixes.   

_Disclaimer:_

_This tool is for educational purposes only. Ensure you have explicit permission before scanning any network or system. Unauthorized port scanning can be illegal._
