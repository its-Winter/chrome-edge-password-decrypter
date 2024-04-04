# Decrypt Chrome Passwords

Decrypt chrome password from a given "Login Data" chrome database and the "Local State" JSON file that contains the key and optionally export output to a CSV file.

## Installation
```
git clone https://github.com/Bruckyy/chrome-password-decrypter.git
cd chrome-password-decrypter
pip install -r requirements.txt
```

## Usage
```
> python .\chrome-decrypt.py --help
usage: chrome-decrypt.py [-h] -k KEY -d DB [-o OUTPUT]

> python chrome-decrypt.py --key local_state_file --db login_data_file -o decrypted_passwords

**************************************************
Sequence: 1
URL: https://www.github.com/login
User Name: <USERNAME>
Password: <PASSWORD>

**************************************************
<SNIP>
...

Exported decrypted passwords to decrypted_passwords.csv

```

## OS support
1. Windows

## Details
This project is a standalone version that takes the files as arguments and a fork of [this](https://github.com/ohyicong/decrypt-chrome-passwords) project
