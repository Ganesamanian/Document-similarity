# Document Similarity #

### What is this repository for? ###

* **Summary**: This repository contains code for Document Similarity Finder, a tool that calculates the similarity between text spans or documents using various natural language processing techniques.
* **Version**: 1.0

### How do I get set up? ###

* **Summary of set up**: To effectively use the Document Similarity Finder code, please follow these steps:

  1. **Clone this repository** to your local machine.
  2. Ensure that you have **Python** (version 3.6 or higher) installed on your system.
  3. Install the required Python packages using the following command:
     ```bash
     pip install requests zipfile glob2 numpy seaborn matplotlib pandas scikit-learn sentence-transformers spacy
     ```
  4. Download the spaCy language model for English:
     ```bash
     python -m spacy download en_core_web_lg
     ```
  5. Organize your text spans or documents in a suitable format.
  6. Use the provided code to calculate document similarity based on your input.

* **Configuration**: No specific configuration is required for this project. The code is designed to work with default settings.

* **Dependencies**: This project relies on the following essential dependencies:
  - **Python** (version 3.6 or higher)
  - **Numpy**
  - **Seaborn**
  - **Matplotlib**
  - **Pandas**
  - **scikit-learn**
  - **sentence-transformers**
  - **spacy** (with the 'en_core_web_lg' language model)

* **Database configuration**: This project does not utilize a database.

* **How to run tests**: Currently, there are no automated tests provided within the repository. You can evaluate the effectiveness of the Document Similarity Finder by following the usage instructions and examining the results.

* **Deployment instructions**: There are no special deployment requirements. Simply clone the repository and utilize the Document Similarity Finder according to your needs.

### Contribution guidelines ###

* **Writing tests**: Contributions that enhance the codebase by adding automated tests are highly encouraged. Ensure that your tests comprehensively cover various scenarios and edge cases.

* **Code review**: If you intend to contribute code improvements or bug fixes, please initiate a pull request. All contributions will undergo a thorough review process to maintain code quality.

* **Other guidelines**: Feel free to open issues for bug reports, feature requests, or any questions or suggestions you may have. Your feedback is invaluable to the project's development.

### Who do I talk to? ###

**Repo owner or admin**: Ganesamanian Kolappan
  - **Email**: kganesamanianthanu@gmail.com