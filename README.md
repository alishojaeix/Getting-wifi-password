# Getting-wifi-password

# Wi-Fi Password Extractor

This Python script extracts saved Wi-Fi profiles and their passwords (if available) on a Windows machine using the `netsh` command.

## Description

The script uses the `subprocess` module to interact with the Windows command line and retrieve Wi-Fi profile information. It then parses the output to extract Wi-Fi names and their corresponding passwords (if stored).

## Features

- Retrieves a list of all saved Wi-Fi profiles.
- Extracts passwords for Wi-Fi profiles (if available).
- Displays the Wi-Fi name and password in a formatted table.

## Prerequisites

- **Operating System**: Windows
- **Python Version**: Python 3.x

## How to Use

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/alishojaeix/Getting-wifi-password.git
   cd wifi-password-extractor
