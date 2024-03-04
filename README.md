# Athena

## Table of Contents

- [About](#about)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

## About

Athena scrapes the website "cyberbackgroundchecks.com" and returns the most useful information.

## Features

 - Returns following information: Name - Age - Address - House Value - Numbers - Passwords
 - Requires 0 Proxies
 - Supports threads
 - EXTREMELY Simple Setup

## Instalation

```bash
# Clone the Github repository
git clone https://github.com/infuscate/Athena.git

# Access the directory and install the required libraries
cd Athena
pip install -r requirements.txt

# Run main.py
python main.py
```

## Usage
### When you run main.py it'll ask you to provide information
```py
email_location = " Enter the full path to the .txt that has the emails you want to check. Example: C:\Users\User\Documents\emails.txt "
results_location = " Enter the full path to the .json where you want the results to appear. Example: C:\Users\User\Documents\results.json "
threads = 5 (The more threads you provide the faster it'll be. 5 - 10 usually works perfect)
```

## License
This project is licensed under the MIT License. You are free to use, modify, and distribute this software.
