# wifi-password

This code retrieves and displays the Wi-Fi names and their corresponding passwords saved on your system.

## Usage

The `subprocess` module to execute Windows command-line instructions for fetching Wi-Fi profiles and their passwords.



3. **Handle Errors**:
    - If a password is unavailable, it displays an empty field.
    - If an encoding error occurs, it displays "ENCODING ERROR".

### Example Output
```
Wi-Fi Name                    |Password
---------------------------------------------
HomeNetwork                   |mypassword123
OfficeNetwork                 |workpass456
PublicWiFi                    |
```

### Disclaimer
- This script is intended for educational purposes only.
- Ensure you have permission to access the Wi-Fi profiles before using this script.

### Requirements
- Windows OS
- Python 3.x

### Run the Script
Save the script to a `.py` file and execute it in a Python environment:
```bash
python wifi_password.py
```
