# Py-DataExtractor

Sample project which showcases Microsoft's new Agent Framework

## Steps

- Run CMD in windows

### From the project directory, run the command:
    code-insiders .

### Install the virtual environment using command in the VSCode terminal:
    uv venv .venv

### Initialize the Project environment:
    uv init

### This will install all sub-packages, see `python/packages` for individual packages.
### It may take a minute on first install on Windows.
pip install agent-framework --pre
-- or --
uv add agent-framework --pre
pip install openai
uv add openai


### Install the pre-requisite packages (Optional):
    uv add pandas
    uv add openpyxl


## Requirements

- Python 3.x
- `openpyxl` or `pandas` (for Excel file handling)

## Installation

```bash
pip install openpyxl
# or
pip install pandas
```

## Usage

1. Place your Excel file in the project directory.
2. Run the script:

```bash
python data_extractor.py input.xlsx output.txt
```

## Author

- **Debasish Biswas**

## Version

- **v1.0.0**
- **Date:** 2024-06-10

## License

MIT License
