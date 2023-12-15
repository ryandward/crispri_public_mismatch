# crispri_public_mismatch

## Quickstart Guide

This repository contains a Python script `mismatch.py` which is used to calculate mismatches. Here's how you can use it:

1. **Install pyenv and pipenv**: If not already installed, you can get `pyenv` [here](https://github.com/pyenv/pyenv#installation) and `pipenv` [here](https://pipenv.pypa.io/en/latest/install/#installing-pipenv).

2. **Clone the repository**: Clone this repository to your local machine using the following command:

    ```bash
    git clone https://github.com/ryandward/crispri_public_mismatch.git
    ```

3. **Navigate to the repository**: Change your current directory to the cloned repository:

    ```bash
    cd crispri_public_mismatch
    ```

4. **Install dependencies and activate the virtual environment**: The Pipfile and Pipfile.lock in the repository already specify the necessary dependencies and Python version. Install the dependencies and activate the virtual environment with:

    ```bash
    pipenv install
    pipenv shell
    ```

5. **Run the script**: You can run the `mismatch.py` script with the following command:

    ```bash
    python mismatch.py mismatches --parameters mismatch_parameters.csv --min 0 --max 1 --step 0.1 --spacers_file U00096.3_sgrna.tsv.gz
    ```

    This command calculates mismatches using parameters from `mismatch_parameters.csv`, with a minimum value of 0, maximum value of 1, step size of 0.1, and spacers file `U00096.3_sgrna.tsv.gz`.

If you encounter any issues, feel free to open an issue in this repository.

# Parameter Data Source 
https://github.com/jordivangestel/sgRNAs-for-mismatch-CRISPRi/blob/main/model_param.csv
