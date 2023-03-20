# RBZ Interbank USD Exchange Rate Scraper

This project is a Python script that downloads the latest pdf file from the RBZ website and extracts the ZWL-USD mid rate.

## Requirements

- Python 3.6 or higher
- beautifulsoup4==4.11.2
- requests==2.28.1
- tabula==1.0.5
- tabula_py==2.7.0
- tabulate==0.9.0

## Installation

1. Clone the repository to your local machine.
2. Install the required packages using pip: `pip install -r requirements.txt`

## Usage

1. Run the script: `python Source.py`

## Screenshots

### RBZ Website

![RBZ Website](/screenshots/rbz page 1.png)
![RBZ Website](/screenshots/rbz page 2.png)

### PDF File

![PDF](/screenshots/interbank rate pdf.png)

The script will extract the ZWL-USD mid rate. 
Here the rate is **ZWL 914.4678 to USD 1**.

### Output
Example output:

```commandline
Getting latest RBZ pdf file...
Getting RBZ ZWL-USD rate...
RBZ ZWL-USD rate: 914.4678
```

## License

This project is licensed under the MIT License - see the LICENSE file for details.
