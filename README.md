# Automation Scripting Lab

A lightweight Python command-line automation tool that uses external dependencies to fetch API data and manage timestamped log files.

## Features
- External API Integration: Fetches sample post data using the requests library.
- Dynamic File Logging: Outputs formatted entries into timestamped files (log_YYYYMMDD.txt).
- Input Validation: Raises a ValueError for non-list log inputs.
- CLI Execution Guard: Uses if __name__ == "__main__": for standalone or modular execution.

## Setup Instructions
- Install Dependencies
pip install -r requirements.txt

- Run the script
python3 lib/generate_log.py

- Run Unit tests
pytest

## Project Structure

```text
├── lib/
│   └── generate_log.py       # Core automation script and log generator
├── testing/
│   └── test_generate_log.py  # Unit test suite
├── requirements.txt          # Project dependencies
└── README.md                 # Documentation


