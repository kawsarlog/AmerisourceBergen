# AmerisourceBergen Price Scraper

![Python Version](https://img.shields.io/badge/Python-3.9.7-blue)
![Selenium Version](https://img.shields.io/badge/selenium-4.1.3-brightgreen)
![Openpyxl Version](https://img.shields.io/badge/openpyxl-3.1.2-brightgreen)
![Webdriver-Manager Version](https://img.shields.io/badge/webdriver--manager-4.0.0-brightgreen)

## DescriptionThis
🛠️ Python 🐍 script automates the extraction of product pricing details from the AmerisourceBergen 🌐 website https://abcorder.amerisourcebergen.com By inputting your ```username```, ```password```, and ```National Drug Code (NDC) codes``` 
and the 📜 script navigates the website and retrieves the 💰 Average Wholesale Price (AWP) and Acquisition Cost (Accq Cost) 📊 data.

### The input data format should be as follows:

| DRUG NAME              | NDC (00000-0000-00) |
|------------------------|---------------------|
| ACTEMRA 200 MG/10 ML VIAL | 50242013601 |
| ZOLEDRONIC 5MG BAG 1X100ML | 25021083082 |
| XOLAIR 150MG/ML PFS 1ML | 50242021501 |
| TYSABRI DS 300 MG VL 15 ML DS | 64406000801 |

![Input XL Format](https://img001.prntscr.com/file/img001/OGw99YhiR_e5e2xUGLfhng.png)

### The extracted output data will be appended in the following format:

| DRUG NAME              | NDC (00000-0000-00) | Average Wholesale Price | Accq Cost |
|------------------------|---------------------|-------------------------|-----------|
| ACTEMRA 200 MG/10 ML VIAL | 50242013601 | $1,593.49 | $641.43 |
| ZOLEDRONIC 5MG BAG 1X100ML | 25021083082 | $420.00 | $14.14 |
| XOLAIR 150MG/ML PFS 1ML | 50242021501 | $1,567.88 | $861.55 |
| TYSABRI DS 300 MG VL 15 ML DS | 64406000801 | $9,851.22 | $1,140.44 |

## Table of Contents
- [Requirements](#requirements)
- [Python Installation](#python-installation)
- [Script Installation](#script-installation)
- [Usage](#usage)
- [Developer Contact](#contact)

## Requirements
Make sure you have the following packages installed:
- Python 3.9.7
- selenium==4.1.3
- openpyxl==3.1.2
- webdriver-manager==4.0.0

You can install these packages using `pip`:

```bash
pip install selenium==4.1.3 openpyxl==3.1.2 webdriver-manager==4.0.0
```


## Python Installation
Before running the AmerisourceBergen Price Scraper, ensure that you have Python installed on your system. To check the Python version, open a terminal (or command prompt) and enter the following command:

```bash
python --version
```

If Python is not installed, you can download it from the official Python website: [Python Downloads](https://www.python.org/downloads/release/python-397/)

Make sure to add Python to your system's PATH variable during the installation. Here's a helpful image to guide you:

![Add Python to PATH](https://camo.githubusercontent.com/96c8ee1f0cc3bbb4145befc07d39dfc629404b8f3dc692298b6419e20714fa33/68747470733a2f2f696d673030312e70726e747363722e636f6d2f66696c652f696d673030312f544e2d6d62647a79547871767130546a6f7a683959512e6a706567)

## Script Installation
1. Clone the repository to your local machine:

```bash
git clone https://github.com/kawsarlog/AmerisourceBergen.git
```

2. Change to the project directory:

```bash
cd AmerisourceBergen
```

3. Install the required packages as mentioned in the Requirements section.

## Usage
1. Edit the script to update your login credentials, input and output file names, URLs, and any other required configuration. ![log in](https://img001.prntscr.com/file/img001/DhEq5UCrRSq7-BomxMOZwA.png)

2. Run the script using the following command:

```bash
python amerisourceberge.py
```

The script will automatically navigate the website, perform data extraction based on the input data, and append the extracted data to the output Excel sheet.

## Contact
For any inquiries or suggestions, feel free to reach out to the developer:

- Website: [http://kawsarlog.com/](http://kawsarlog.com/)
- Email: [kawsarlog@gmail.com](mailto:kawsarlog@gmail.com)
- LinkedIn: [https://www.linkedin.com/in/kawsarlog](https://www.linkedin.com/in/kawsarlog)

---

**Note:** This script should be used responsibly and in compliance with the Website's Terms of Service.
