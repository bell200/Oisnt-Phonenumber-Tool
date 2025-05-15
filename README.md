# Oisnt-Phonenumber-Tool

An Open Source Intelligence (OSINT) tool for analyzing and verifying phone numbers using public APIs, leaked metadata files, and external CLI tools like TruecallerJS.

## 🚀 Features

- Validates phone numbers using the [apilayer.net](https://apilayer.com/) API.
- Displays location, carrier, country, and line type.
- Searches local metadata files per country (e.g., israel.txt, germany.txt).
- Integrates with TruecallerJS for identity lookup.
- Command-line interface with ASCII banner.
- Optional: Detects phone numbers in publicly leaked metadata (manual files).

## 🛠 Tech Stack

- Python 3
- `phonenumbers`
- `requests`
- `subprocess`
- `art`
- `grep` (Unix-based)

## 📸 Screenshot

![Example output](screenshots/example_output.png)

## 📂 File Structure

```bash
.
├── main.py                # Main CLI tool
├── requirements.txt       # Python dependencies
├── country_data/          # Phone number lists by country
└── README.md              # Project description
