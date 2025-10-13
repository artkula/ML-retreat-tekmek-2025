# ML Retreat Tekmek 2025

## Mission

- **Familiarise** with ML terminology
- **See and try** simple methods
- **Calibrate** expectations about the power of Machine Learning
- **Recognize** the importance of domain knowledge for applying these methods

### Goal

Get genuinely interested in data-driven methods and AI!

## Running the Notebooks

### Option 1: Google Colab (Easiest - No Setup Required)

The simplest way to run these notebooks is using Google Colab. Each notebook has an "Open in Colab" button at the top that will take you directly to Google Colab where you can run the notebook in your browser without any installation.

1. Open any `.ipynb` notebook file in this repository
2. Look for the "Open in Colab" button at the top of the notebook
3. Click it to open the notebook in Google Colab
4. Run the cells directly in your browser - all dependencies are already available!

### Option 2: VS Code (Local Setup)

### Prerequisites
- [Python 3.8 or higher](https://www.python.org/downloads/) installed
- [VS Code](https://code.visualstudio.com/) with the [Python extension](https://marketplace.visualstudio.com/items?itemName=ms-python.python) installed

### Installation Steps

1. **Clone or download this repository** to your local machine

2. **Open the project folder in VS Code**
   - File > Open Folder > Select the `ML-retreat-tekmek-2025` folder

3. **Create a virtual environment** (recommended)
   - Open the integrated terminal in VS Code (Terminal > New Terminal)
   - Run:
     ```bash
     python -m venv venv
     ```

4. **Activate the virtual environment**
   - On Windows:
     ```bash
     venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```bash
     source venv/bin/activate
     ```

5. **Install required packages**
   - With the virtual environment activated, run:
     ```bash
     pip install -r requirements.txt
     ```
   - This will install all necessary dependencies including:
     - NumPy, Pandas, Matplotlib, SciPy
     - Scikit-learn
     - TensorFlow/Keras
     - PySINDy
     - Jupyter and ipywidgets
     - And more!

6. **Select the Python interpreter in VS Code**
   - Press `Ctrl+Shift+P` (or `Cmd+Shift+P` on macOS)
   - Type "Python: Select Interpreter"
   - Choose the interpreter from your virtual environment (should show `./venv/Scripts/python.exe`)

7. **Open and run Jupyter notebooks**
   - Open any `.ipynb` file in the project
   - VS Code will automatically detect it as a Jupyter notebook
   - Click "Run All" or run cells individually
   - Make sure the kernel shows your virtual environment's Python interpreter

### Troubleshooting

- If Jupyter kernels don't appear, try installing `ipykernel`:
  ```bash
  pip install ipykernel
  ```
- If widgets don't display properly, ensure `ipywidgets` is installed
- Make sure your virtual environment is activated before running pip install commands
