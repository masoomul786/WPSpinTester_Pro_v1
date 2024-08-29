# WPSpinTester Pro v1

WPSpinTester Pro v1 is a WiFi testing tool designed for testing the security of WiFi networks using the WPS PIN technique. This tool is intended to be used for educational purposes only. It provides a user-friendly interface to facilitate the process of testing WPS PINs against WiFi networks, helping users understand the importance of securing their networks.

## Description

WPSpinTester Pro v1 allows users to:

- **Load Custom Payloads**: Import a list of WPS PINs from a text file to test against WiFi networks.
- **Use Default Payload**: Automatically generate a default list of PINs for testing.
- **Scan WiFi Networks**: Detect and list available WiFi networks in your vicinity.
- **Connect to Network**: Attempt to connect to a selected WiFi network using the provided WPS PINs.
- **Track Progress**: Monitor the progress of the PIN testing process.

This tool does not require a WiFi adapter to operate; it relies on the WPS PIN technique to attempt connections. It is designed to help users understand the vulnerabilities associated with WPS and emphasize the need for robust network security.

## Features

- **Custom Payload Loading**: Load PINs from a user-provided text file.
- **Default PIN List**: Use a predefined list of common WPS PINs.
- **Network Scanning**: Identify and display nearby WiFi networks.
- **Network Connection Attempts**: Test WPS PINs on selected networks.
- **Progress Updates**: Visual feedback on the testing progress.

## Installation

1. **Clone the Repository**

    ```bash
    git clone https://github.com/masoomul786/WPSpinTester_Pro_v1.git
    ```

2. **Navigate to the Project Directory**

    ```bash
    cd WPSpinTester-Pro-v1
    ```

3. **Install Dependencies**

    To install the required Python packages, use the `requirements.txt` file:

    ```bash
    pip install -r requirements.txt
    ```

4. **Run the Application**

    Execute the application using:

    ```bash
    python main.py
    ```

## Usage

1. **Load Custom Payload**: Click "Load Custom Payload" to select a text file containing a list of WPS PINs.
2. **Use Default Payload**: Click "Use Default Payload" to utilize a preset list of common WPS PINs.
3. **Scan WiFi Networks**: Click "Scan WiFi Networks" to display available WiFi networks.
4. **Connect to Network**: Select a network and click "Connect to Network" to start testing WPS PINs.
5. **Stop**: Click "Stop" to halt the ongoing process.

## Screenshots

![WPSpinTester Pro v1 Screenshot]!![wps](https://github.com/user-attachments/assets/c0c77c7f-3577-4ac4-9aca-1d991372d489)


enshot.png)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Disclaimer

This software is provided solely for educational purposes. Unauthorized use of this tool to access networks without permission is illegal and unethical. Ensure you have explicit permission to test any network. The developers of this software assume no responsibility for any misuse or damage caused by the use of this tool.
