# ChatGPT-4 TDD Assistant for Brazilian Gas Prices Data Analysis

This is an experimental project utilizing ChatGPT-4 to assist Test-Driven Development (TDD) in the creation of a software solution. The software is intended to analyze a dataset on Brazilian gas prices using Pandas and Numpy. This project uses Python 3.9+ and manages dependencies through Poetry.

## Requirements
- Python 3.9+
- Poetry (Dependency Manager)
- PyTest (For test development)
- Pandas (For Data Manipulation)
- Numpy
- An instance of ChatGPT-4 (For Test-Driven Development Assistance)

## Project Structure

```
.
├── LICENSE
├── README.md
├── __init__.py
├── datasets
│   └── brazilian_gas_prices_2004-2021.tsv
├── main.py
├── pyproject.toml
└── src
```

## Setup Instructions

### For Mac OSX:

1. Clone the repository:

    ```
    git clone https://github.com/jguilhermemv/gasPricesBrazilAnalysis.git
    cd chatgpt4_tdd_data_analysis
    ```

2. Install Python 3.9+ if not already installed. You can download it from the official Python website or use Homebrew:

    ```
    brew install python@3.9
    ```

3. Install Poetry. The recommended way is through `curl`:

    ```
    curl -sSL https://install.python-poetry.org | python -
    ```

4. Use Poetry to install the project dependencies:

    ```
    poetry install
    ```

5. You are now ready to run and develop the project.

### For Windows:

1. Clone the repository:

    ```
    git clone https://github.com/user/chatgpt4_tdd_data_analysis.git
    cd chatgpt4_tdd_data_analysis
    ```

2. Install Python 3.9+ if not already installed. You can download it from the official Python website or use the Windows package manager `choco`:

    ```
    choco install python --version=3.9.7
    ```

3. Install Poetry. The recommended way is through PowerShell:

    ```
    (Invoke-WebRequest -Uri https://install.python-poetry.org -UseBasicParsing).Content | python -
    ```

4. Use Poetry to install the project dependencies:

    ```
    poetry install
    ```

5. You are now ready to run and develop the project.

## Usage

Once the project is set up, you can start writing tests with the assistance of ChatGPT-4 and then proceed to develop your data analysis program.

This project is experimental, and feedback is greatly appreciated. Please report any issues or suggestions to the project's issue tracker on GitHub.

## License

This project is licensed under the Apache 2.0 License. See `LICENSE` for more information.