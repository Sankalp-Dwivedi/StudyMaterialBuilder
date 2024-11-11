# Study Material Builder

A tool that automates the creation of study materials based on a given topic. This project leverages web scraping to gather relevant information and uses transformer models to organize and process the data into structured study materials. Additionally, it generates a PDF and a video lecture for comprehensive learning.

## Features

- **Automated Content Generation**: Takes a topic as input and generates well-structured study materials.
- **Web Scraping**: Scrapes the web for relevant, reliable content on the provided topic.
- **Transformer Models**: Utilizes NLP models to summarize and enhance the gathered information.
- **PDF Generation**: Exports the study material to a downloadable PDF format.
- **Video Lecture Creation**: Generates a lecture video based on the created study material.

## Getting Started

### Prerequisites

- Python 3.x
- Required libraries (install via `requirements.txt`)
- Transformer models (e.g., Hugging Face transformers)

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/study-material-builder.git
   cd study-material-builder

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   
- Set up any necessary API keys or environment variables for web scraping and transformer models.

### Usage

1. Run the main script and provide a topic:

   ```bash
   run all the shells of ipynb file in sequence

2. The program will scrape data, process it using transformer models, and organize the information into structured study content.

3. Generated outputs:

- PDF file containing study material.
- Video lecture file based on the study material.


### Example

    ```bash
    Enter the topic: Quantum Mechanics
    Generating study materials for "Quantum Mechanics"...
    Creating PDF...
    Generating video lecture...
  
The output files (PDF and video) will be saved in the designated output directory.

## Technologies Used

- Python
- BeautifulSoup & Scrapy for web scraping
- Transformers library for NLP tasks
- ReportLab for PDF generation
- MoviePy or other multimedia libraries for video creation

## Future Enhancements

- Add more customization options for video lecture styles.
- Expand web scraping sources to increase content quality.
- Improve transformer model tuning for more accurate summarizations.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any bug fixes, features, or improvements.

## License
This project is licensed under the MIT License.
