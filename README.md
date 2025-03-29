# Roblox Client Cookie Stealer

**Roblox Client Cookie Stealer** is a Python script designed to retrieve, decode, and decrypt Roblox cookies stored on your Windows machine. The script extracts the .ROBLOSECURITY cookie, It then prints the full cookie data

# Important Warning:
- Never share your Roblox cookies with anyone. Sharing these cookies allows someone to log in as you and steal your items and Robux.

## Features
- Retrieves Roblox cookies stored in the user's profile.
- Decodes the cookie data from base64 encoding.
- Decrypts Roblox cookies using Windows DPAPI (Data Protection API).
- Extracts and displays the warning message related to sharing Roblox cookies.
- Outputs the .ROBLOSECURITY cookie, the warning message, and the decrypted cookie data.

## Requirements
To run this script, you'll need the following:

- Python 3.x installed on your system.
- pywin32 package to interact with Windows DPAPI for decryption.

You can install the required package using pip:
```bash
pip install pywin32
```
## Usage
1. Clone the Repository
Clone the repository to your local machine using the following command:

```bash
git clone https://github.com/Ramona-Flower/Roblox-Client-Cookie-Stealer.git
```

2. Run the Script
- Ensure you have Python 3 installed. Then, navigate to the project directory and run the script:
```
python main.py
```

The script will:

- Locate the Roblox cookies file stored on your system.
- Decode the cookies data from base64.
- Decrypt the cookies using Windows DPAPI.
- Extract and print the .ROBLOSECURITY cookie, along with the warning message and the remaining decrypted content.

Output
After running the script, you should see output similar to this:
```
Final Output:
.ROBLOSECURITY  DO-NOT-SHARE-THIS.--Sharing-this-will-allow-someone-to-log-in-as-you-and-to-steal-your-ROBUX-and-items.|...
```
This will print the .ROBLOSECURITY cookie, and all the data

## Feel free to open Issue/Pull Requests if you need something
## Disclaimer
This script is for educational purposes only. The author of this repository is not responsible for any misuse or unauthorized access to Roblox accounts. Please use this script responsibly and only on accounts that you own.

## License
This project is licensed under the APACHE License 2.0 - see the LICENSE file for details.
