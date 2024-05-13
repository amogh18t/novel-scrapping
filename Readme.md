# Web Scrapping and Named Entity Recognition (NER)

This program uses web scraping to extract the text from a website and then uses Named Entity Recognition (NER) to find the name of the main character, MC.

## How it works

pip install -r requirements.txt

The program uses the following libraries:

* `requests` to send a GET request to the website and get the HTML content
* `BeautifulSoup` to parse the HTML content and extract the text
* `spaCy` to perform NER on the extracted text

The program first sends a GET request to the website and gets the HTML content. It then uses BeautifulSoup to parse the HTML content and extract the text from the website. Finally, it uses spaCy to perform NER on the extracted text. If the program finds the name of the main character, MC, it outputs the name to the console.

## How to use this program

To use this program, you need to have the following installed:

* Python 3.x
* The requests library
* The BeautifulSoup library
* The spaCy library

You can install these libraries using pip by running the following command:

