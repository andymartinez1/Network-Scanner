# NetworkScanner

## Overview

NetworkScanner is a basic but efficient tool designed to scan and analyze network devices.

## Features

- Fast and accurate network scanning
- Detection of active devices
- Identification of potential vulnerabilities
- User-friendly command-line interface

## Installation

To install NetworkScanner, follow these steps:

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/NetworkScanner.git
   ```
2. Navigate to the project directory:
   ```sh
   cd NetworkScanner
   ```
3. Install the required dependencies:

   ```sh
   pip install scapy
   ```

   ## Usage

   To use NetworkScanner, run the following command:

   ```sh
   python3 network_scanner.py
   ```

   You can also specify additional options:

   - `-t` or `--target`: Specify the target IP address or subnet.

   Example:

   ```sh
   python3 network_scanner.py -t 192.168.0.0/24
   ```

   ## Contributing

   We welcome contributions! Please follow these steps to contribute:

   1. Fork the repository.
   2. Create a new branch:
      ```sh
      git checkout -b feature-branch
      ```
   3. Make your changes and commit them:
      ```sh
      git commit -m "Description of your changes"
      ```
   4. Push to the branch:
      ```sh
      git push origin feature-branch
      ```
   5. Create a pull request.
