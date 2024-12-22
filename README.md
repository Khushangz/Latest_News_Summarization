
# Web Scraping Times of India (TOI)

This project demonstrates how to scrape articles from the Times of India (TOI) website using Python. It extracts relevant news content, such as headlines, article bodies, publication dates, and authors, and stores the data in a structured format for further analysis. The project also utilizes **Transformers** for summarizing articles and **spaCy** for data filtration.

## Table of Contents

- [Project Overview](#project-overview)
- [Installation](#installation)
- [Usage](#usage)
- [Requirements](#requirements)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

This notebook aims to scrape and analyze articles from TOI. It includes steps to:
- Connect to the TOI website.
- Extract headlines, article texts, and metadata.
- Use **spaCy** for data filtration and processing of the extracted text.
- Utilize **Hugging Face Transformers** to summarize articles.
- Store the extracted data in a structured format for later use in data analysis or sentiment analysis.

## Installation

To run the code, clone this repository and install the required dependencies:

```bash
git clone <repository-url>
cd <repository-directory>
pip install -r requirements.txt
```

## Usage

1. Open the Jupyter notebook file `Scrapping_TOI.ipynb`.
2. Run the cells in sequence to scrape articles from TOI.
3. Modify the base URL, if needed, to target different sections of TOI.
4. The extracted data will be filtered using **spaCy** and summarized using **Transformers**.
5. The final data will be displayed or saved based on the configuration in the notebook.

### Example Usage

```python
# Example of running the notebook
python scrape_toi.py
```

## Requirements

- Python 3.x
- Jupyter Notebook
- Libraries: `requests`, `BeautifulSoup`, `pandas`, `time`, `re`, `transformers`, `spacy`

You can install all the necessary libraries using the following command:

```bash
pip install -r requirements.txt
```

## Project Structure

```bash
├── Scrapping_TOI.ipynb  # Main notebook for scraping TOI articles
├── requirements.txt     # Required Python libraries
└── README.md            # Project documentation
```

## Contributing

Feel free to submit a pull request or create an issue if you have suggestions for improving the project.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
