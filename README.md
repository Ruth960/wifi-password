# wifi-password

This code retrieves and displays the Wi-Fi names and their corresponding passwords saved on your system.
#N/B
    You can only seen the wifi password if you had          logged in before.

## Usage

The `subprocess` module to execute Windows command-line instructions for fetching Wi-Fi profiles and their passwords.



3. **Handle Errors**:
    - If a password is unavailable, it displays an empty field.

### Example Output
```
Wi-Fi Name                    |Password
---------------------------------------------
HomeNetwork                   |mypassword123
OfficeNetwork                 |workpass456
PublicWiFi                    |
```
### Requirements
- Windows OS
- Python 3.x

### Run the Script
Save the script to a `.py` file and execute it in a Python environment:
```bash
python wifi_password.py
```
