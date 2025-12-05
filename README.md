# Workshop-CES-UoB-UC
Repository for the Cryogenic Energy Storage Workshop at the University of Birmingham, in collaboration with Pontificia Universidad Católica de Chile.

 # Instalation
## Prerequisites
To get started, install [Miniconda](https://docs.conda.io/en/latest/miniconda.html) or [Anaconda](https://www.anaconda.com/products/distribution) for Python environment management. We also recommend using [Visual Studio Code](https://code.visualstudio.com/) as your code editor.

## Environment Setup
After installing Conda, open the Anaconda Prompt (or Miniconda terminal), navigate to the repository folder, and execute the following command:

```bash
# Create environment from file
conda env create -f environment.yml
```

## Execute example code
Go to "notebooks" folder and open a Jupyter Notebook. Then, to run CryoeEvap software, you have to activate your environment and make sure to include these two lines of code in order to include the software to the path:

```python
 # Adds higher directory to python modules path.
import sys
sys.path.append("../CryoEvap/")
```

