# intellihack

To set up a Python environment and install the necessary dependencies from a `requirements.txt` file for running the crop prediction notebook, follow these detailed steps:

### Step 1: Install Python
Ensure that Python is installed on your system. You can download and install the latest version from [python.org](https://www.python.org/downloads/).

### Step 2: Create a Virtual Environment
Creating a virtual environment is recommended to manage the dependencies for your project separately from other Python projects. Here’s how you can do it:

1. Open your command line interface (CLI), such as Terminal on macOS or Command Prompt on Windows.
2. Navigate to the project directory where you want the virtual environment to be set up:
   ```bash
   cd path/to/your/project
   ```
3. Run the following command to create a virtual environment named `env`:
   ```bash
   python -m venv env
   ```

### Step 3: Activate the Virtual Environment
Before installing the dependencies, activate the virtual environment:

- **On macOS and Linux**:
  ```bash
  source env/bin/activate
  ```
- **On Windows**:
  ```bash
  env\Scripts\activate
  ```

### Step 4: Install Dependencies
With the virtual environment activated, install the dependencies specified in the `requirements.txt` file:

1. Ensure that the `requirements.txt` file is in the project directory or specify the path to it.
2. Install the dependencies using pip:
   ```bash
   pip install -r requirements.txt
   ```

### Step 5: Verify Installation
After installation, you can verify that the correct packages were installed by listing them:
```bash
pip list
```

### Step 6: Running the Notebook
With the environment set up and dependencies installed, you can now run the Jupyter notebook:

1. Install JupyterLab or Jupyter Notebook if you haven’t already:
   ```bash
   pip install jupyterlab
   ```
2. Start JupyterLab or Notebook:
   ```bash
   jupyter lab
   ```
   or
   ```bash
   jupyter notebook
   ```
3. Open the notebook file (`Crop Prediction.ipynb`) in the Jupyter interface that opens in your browser.
4. Run the notebook cells sequentially by pressing `Shift + Enter` on each cell or using the run button in the interface.

These steps will ensure that you have a functional Python environment ready for executing and exploring the crop prediction model.
