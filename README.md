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

<img width="960" alt="rbz page 1" src="https://user-images.githubusercontent.com/63872314/226336501-c5ac3e08-6ae7-4e6a-901d-4a053fdab0ff.PNG">
<img width="960" alt="rbz page 2" src="https://user-images.githubusercontent.com/63872314/226336603-5161db1c-17f9-475b-a79d-2411c6a34bea.PNG">

### PDF File

<img width="960" alt="interbank rate pdf" src="https://user-images.githubusercontent.com/63872314/226336665-6a35982a-f9ef-46d6-9e83-edd050d74d83.PNG">


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
