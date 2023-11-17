# crispri_public_mismatch

## Quickstart Guide

This repository contains a Python script `mismatch.py` which is used to calculate mismatches. Here's how you can use it:

1. **Install Python**: Make sure you have Python installed on your machine. If not, you can download it from [here](https://www.python.org/downloads/).

2. **Install pyenv**: To manage Python versions, install `pyenv` using the instructions provided [here](https://github.com/pyenv/pyenv#installation).

3. **Set Python version**: Set your Python version to 3.11.5 (as specified in the Pipfile) for the local project directory using the following command:

    ```bash
    pyenv install 3.11.5
    pyenv local 3.11.5
    ```

4. **Install pipenv**: Install `pipenv` for managing dependencies:

    ```bash
    pip install pipenv
    ```

5. **Clone the repository**: Clone this repository to your local machine using the following command:

    ```bash
    git clone ryandward/crispri_public_mismatch
    ```

6. **Navigate to the repository**: Change your current directory to the cloned repository:

    ```bash
    cd crispri_public_mismatch
    ```

7. **Install dependencies**: Install the required dependencies using `pipenv`:

    ```bash
    pipenv install
    ```

8. **Activate the virtual environment**: Activate the `pipenv` shell:

    ```bash
    pipenv shell
    ```

9. **Run the script**: You can run the `mismatch.py` script with the following command:

    ```bash
    python mismatch.py mismatches --parameters mismatch_parameters.csv --min 0 --max 1 --step 0.1 --spacers_file U00096.3_sgrna.tsv.gz
    ```

    This command calculates mismatches using parameters from `mismatch_parameters.csv`, with a minimum value of 0, maximum value of 1, step size of 0.1, and spacers file `U00096.3_sgrna.tsv.gz`.

Please replace `<repository_url>` with the actual URL of this repository.

If you encounter any issues, feel free to open an issue in this repository.
