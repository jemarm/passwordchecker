# Password Checker

This Python script allows you to check if your passwords have been compromised in any known data breaches using the Pwned Passwords API (https://haveibeenpwned.com/Passwords).

## Prerequisites

- Python 3.x
- `requests` library (install using `pip install requests`)

The script will check each password against the Pwned Passwords database and inform you if any of them have been compromised.

## Security Note

- This script does not send your passwords over the internet. It only sends the first five characters of the password hash to the Pwned Passwords API and then processes the response locally.

## Disclaimer

- This script is provided as-is and does not guarantee the security of your passwords. It is always recommended to use unique and strong passwords for each online account and to enable two-factor authentication whenever possible.

## Acknowledgements

- This project is from ZTM course by Andrei Neagoie was inspired by the work of Troy Hunt and the Have I Been Pwned project (https://haveibeenpwned.com/).

## License

- This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
