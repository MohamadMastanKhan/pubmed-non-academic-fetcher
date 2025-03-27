Fetch PubMed Papers

Description

This Python script fetches research papers from PubMed based on a user-specified query. It identifies papers with at least one author affiliated with a pharmaceutical or biotech company and returns the results as a CSV file.

Features

Fetch research papers from PubMed using their API.

Identify non-academic authors based on affiliation.

Extract information such as PubmedID, title, publication date, non-academic authors, company affiliations, and corresponding author email.

Support for command-line arguments.

Option to save results to a CSV file.

Debug mode for troubleshooting.

Installation

This project uses Poetry for dependency management.

Steps to Install:

Clone the repository:

git clone https://github.com/your-username/fetch_pubmed_papers.git
cd fetch_pubmed_papers

Install Poetry:

pip install poetry

Install dependencies:

poetry install

Usage

Run the script using the following command:

python fetch_pubmed_papers.py "<your_query>" -f output.csv

Command-line Options:

-h, --help: Display usage instructions.

-d, --debug: Enable debug mode.

-f, --file <filename>: Specify the output CSV filename.

Example:

python fetch_pubmed_papers.py "cancer treatment" -f papers.csv

Project Structure

fetch_pubmed_papers/
│── fetch_pubmed_papers.py  # Main script
│── README.md               # Project documentation
│── pyproject.toml          # Poetry configuration
│── poetry.lock             # Dependency lock file

API Information

This project uses the PubMed API.

Contributing

Feel free to contribute by submitting a pull request.

License

This project is open-source and available under the MIT License.

