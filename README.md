# Piazza Helpful Comments Counter

This program logs into a Piazza course using provided credentials, fetches all posts, and counts the number of helpful ('good') comments made by each student. It then exports this data to an Excel file.

## Setup

1. Install the required Python libraries with pip:

```bash
pip install piazza-api pandas html2text
```

2. Replace EMAIL, PASSWORD, and NETWORK_ID in the main function with your Piazza email, password, and the network ID of your course.

## Usage

```bash
python main.py
```

The program will create an Excel file with the current date and time as the filename, containing the student IDs, names, and counts of helpful comments.

## Note

This program uses the unofficial piazza-api Python library to interact with Piazza. Use at your own risk.