# Proxy Checker

This script is a general-purpose proxy checker that can be used to check a list of email:password combinations against a specified URL.

## Requirements

- Python 3.x
- Requests library

## Installation

1. Clone the repository:
```
git clone https://github.com/BeingPhoenix/Proxy-Checker.git
```
2. Navigate to the project directory:
```
cd proxy-checker
```
3. Install the required dependencies:
```
pip install -r requirements.txt
```
## Usage

1. Add your email:password combinations to the `combos.txt` file, each on a new line in the format `email:password`.

2. Update the `url` variable in the `checker()` function with the desired URL to check against.

3. Run the script:
```
python checker.py
```
4. The script will check the provided combos and write the valid ones to the `Results` directory.

## License

This project is licensed under the [MIT License](LICENSE).
