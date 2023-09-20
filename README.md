# Zerodha Selenium Automation

## Introduction

This script automates the login process on the Zerodha platform using Selenium, 
generates a Two-Factor Authentication (2FA) code using PyOTP, and performs further actions within seconds.
## Features
- Automates Zerodha login and 2FA code generation.
- Simplifies repetitive tasks for Zerodha trading.
## Requirements
- Python 3.x
- Selenium
- webdriver-manager
- PyOTP

Install the required packages using:

```bash
pip install -r requirements.txt
```
## Usage 
1. Clone this repository:

```bash
git clone https://github.com/meyanksingh/zerodha-login-selenium
```
2. Navigate to the project directory:
```bash
cd zerodha-login-selenium
```
3. Replace the following placeholders with your Zerodha credentials:

- 'xxx' with your Zerodha User ID
- 'x@xxx' with your Zerodha Password
- 'xxx' with your PyOTP secret key (the TOTP key)
4. Save the Changes
5. Run the script:
```bash
python zerodha_login.py
```

The script will automate the login process, generate a 2FA code using PyOTP, and perform further actions on the Zerodha platform.


## Contributing

Feel free to contribute to this project by opening issues, providing feedback, or submitting pull requests. Your contributions are welcome and appreciated!

## License

This project is licensed under the MIT License.

## Contact

- Email: meyank@itrenzy.com
- LinkedIn: [Meyank Singh](https://www.linkedin.com/in/meyank-singh)

---
