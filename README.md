# Data Science Course

As a professor, in this repo you will find all the practical examples done during class for the course Data Science in Python for Cenfotec University.

## How to Setup Python Environment

### 1. Create Virtual environment

In the root of the proyect create the environment:
``` bash
python3 -m venv venv
```

### 2. Activate Virtual environment

Then, activate the environment in your Terminal:

#### Linux and MacOS
``` bash
source venv/bin/activate
```

#### Windows CMD
``` bash
venv\Scripts\activate.bat
```

#### Windows Powershell
``` bash
venv\Scripts\Activate.ps1
```

You have to use this command each time you create a new Terminal.

### 3. Install dependencies from requirements.txt

Instead of installing dependencies one by one, you list them in the `requirements.txt` file and them install them with pip.

``` bash
pip install -r requirements.txt
```