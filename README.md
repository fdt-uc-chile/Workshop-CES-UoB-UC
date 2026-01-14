# Workshop-CES-UoB-UC
Repository for the Cryogenic Energy Storage Workshop at the University of Birmingham, in collaboration with Pontificia Universidad Católica de Chile.

# Installation Guide

## Prerequisites
Before starting, ensure you have the following tools installed:
- [Miniconda](https://docs.conda.io/en/latest/miniconda.html) or [Anaconda](https://www.anaconda.com/products/distribution) for Python environment management.
- [Visual Studio Code](https://code.visualstudio.com/) as your code editor (recommended).

## Step 1: Clone the Workshop Repository
Use the Git console or Git Desktop App to clone the workshop repository:
```bash
git clone https://github.com/fdt-uc-chile/Workshop-CES-UoB-UC.git
```

## Step 2: Set Up the Conda Environment
1. Open the Anaconda Prompt (or Miniconda terminal).
2. Navigate to the folder where you cloned the repository.
3. Create the Conda environment using the provided `environment.yml` file:
    ```bash
    conda env create -f environment.yml
    ```

## Step 3: Install CryoEvap
### Clone the CryoEvap Repository
For better organization, clone the CryoEvap repository into the same folder as the Workshop repository:
```bash
git clone https://github.com/felipehuerta17/CryoEvap.git
```

### Activate the Conda Environment
Activate the Conda environment created for the workshop in Anaconda Prompt:
```bash
conda activate cryoevap-workshop
```

### Install CryoEvap in Editable Mode
1. Navigate to the directory where you cloned the CryoEvap repository:
    ```bash
    cd /path/to/CryoEvap
    ```
2. Install CryoEvap in editable mode:
    ```bash
    pip install -e .
    ```

You are now ready to use CryoEvap. Feel free to modify the base code in your local version as needed.

## Execute example code
Go to "notebooks" folder and open a Jupyter Notebook. Then, to run CryoeEvap software, you have to activate your environment or detect it using VSCode.


