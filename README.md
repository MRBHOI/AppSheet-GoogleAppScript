<<<<<<< HEAD
# Pincode Lookup App

A simple Tkinter-based desktop application to look up Indian postal pincode details using the India Post API.

## Features

- Sign up and login with email
- Enter a 6-digit pincode and fetch details
- Display district, state, and region for the pincode
- Cache fetched pincode details locally in memory
- Save lookup history and export data to JSON files

## Requirements

- Python 3.x
- `tkinter` (usually included with Python)
- `requests`

## Installation

1. Open a terminal.
2. Install the required package:

```bash
pip install requests
```

## Usage

From the project folder:

```bash
python assignment
```

Then use the GUI to sign up, log in, and look up pincodes.

## Data Export

Click `Save & Export` in the app to export:
- `users.json`
- `pincode_input.json`
- `pincode_details.json`

The files are saved to:
- `mnt/user-data/outputs`

## Notes

- The app validates that pincodes are exactly 6 digits.
- Network requests are done in a background thread to keep the UI responsive.
- Duplicate pincode lookups reuse cached details when available.
=======
# AppSheet-GoogleAppScript
Build a simple app where a user enters a pincode and gets location details automatically
>>>>>>> f1571fe2c5e72e1e1648dd6331a51d62a87661e7
