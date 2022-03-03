# python-word-count-beam by Rohit Reddy Chandupatla

# All of these commands should be run in Powershell.

### Set up your environment

• Check your Python version

The Beam SDK requires Python users to use Python version 3.6 or higher. Check your version by running:

```
python --version
```

### Install pip

Install pip, Python’s package manager. Check that you have version 7.0.0 or newer by running:

```
pip --version
```

**If you do not have pip version 7.0.0 or newer, run the following command to install it. This command might require administrative privileges.**

```
python -m pip install --upgrade pip
```

## Get Apache Beam

### Create and activate a virtual environment

A virtual environment is a directory tree containing its own Python distribution. To create a virtual environment, run:
```
python -m venv C:\Users\s542423\Documents\44517\python-word-count-beam
```
A virtual environment needs to be activated for each shell that is to use it. Activating it sets some environment variables that point to the virtual environment’s directories.

To activate a virtual environment in Bash, run:
```
C:\Users\s542423\Documents\44517\python-word-count-beam\Scripts\activate.ps1\
```

### Download and install

Install the latest Python SDK from PyPI:
```
python -m pip install apache-beam
```
### Execute a pipeline
The Apache Beam examples directory has many examples. All examples can be run locally by passing the required arguments described in the example script.

For example, run wordcount.py with the following command:
```
python -m wordcount --input sample.txt --output Rohit
```


