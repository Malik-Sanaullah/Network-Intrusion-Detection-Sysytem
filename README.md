# Network Intrusion Detection System (NIDS)

## Prerequisites

Before running this project, make sure you have:

* Python 3.10 or later installed
* Internet connection (for installing required packages)
* Terminal/Command Prompt access

---

# Step-by-Step Guide to Run the Project

## Step 1: Open Terminal

Open your system terminal:

### Windows

* Press `Win + R`
* Type `cmd`
* Press Enter

### Linux

* Open Terminal from Applications

### macOS

* Open Terminal from Launchpad

---

## Step 2: Update the System

### Ubuntu/Linux

```bash
sudo apt update
sudo apt upgrade -y
```

### Windows

Make sure Python and pip are updated.

```bash
python -m pip install --upgrade pip
```

---

## Step 3: Install Python (If Not Installed)

Check whether Python is already installed:

```bash
python --version
```

or

```bash
python3 --version
```

If Python is not installed, download it from:

https://www.python.org/downloads/

---

## Step 4: Install Jupyter Notebook

Install Jupyter Notebook using pip:

```bash
pip install notebook
```

Verify installation:

```bash
jupyter notebook --version
```

---

## Step 5: Create a Virtual Environment

Navigate to your project directory:

```bash
cd path/to/project
```

Create a virtual environment:

```bash
python -m venv nids_env
```

---

## Step 6: Activate the Virtual Environment

### Windows

```bash
nids_env\Scripts\activate
```

### Linux/macOS

```bash
source nids_env/bin/activate
```

You should see:

```bash
(nids_env)
```

at the beginning of your terminal line.

---

## Step 7: Install Required Libraries

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

If your project uses additional libraries, install them as well.

You can also install all dependencies using:

```bash
pip install -r requirements.txt
```

(if a requirements.txt file is provided).

---

## Step 8: Register the Environment as a Jupyter Kernel

Install IPython kernel:

```bash
pip install ipykernel
```

Register the environment:

```bash
python -m ipykernel install --user --name=nids_env
```

---

## Step 9: Launch Jupyter Notebook

Start Jupyter Notebook:

```bash
jupyter notebook
```

Your default web browser will open automatically.

If it does not open automatically, copy and paste the displayed URL into your browser.

---

## Step 10: Upload the Project Notebook

In Jupyter Notebook:

1. Click **Upload**
2. Select the file:

```text
Network_Intrusion_Detection_System.ipynb
```

3. Click **Upload** again to confirm.

---

## Step 11: Open the Notebook

Click on:

```text
Network_Intrusion_Detection_System.ipynb
```

to open the notebook.

---

## Step 12: Select the Correct Kernel

From the menu:

```text
Kernel → Change Kernel → nids_env
```

Select the virtual environment kernel created earlier.

---

## Step 13: Run the Notebook

To run each cell:

### Method 1

Press:

```text
Shift + Enter
```

### Method 2

Click:

```text
Run → Run All Cells
```

This will execute the entire notebook from beginning to end.

---

## Expected Output

The notebook will:

* Load the network traffic dataset
* Perform preprocessing
* Train machine learning models
* Evaluate model performance
* Display graphs and visualizations
* Generate intrusion detection results

---

## Troubleshooting

### Jupyter command not found

Install Jupyter again:

```bash
pip install notebook
```

---

### ModuleNotFoundError

Install the missing library:

```bash
pip install library_name
```

Example:

```bash
pip install pandas
```

---

### Kernel Not Found

Register the kernel again:

```bash
python -m ipykernel install --user --name=nids_env
```

---

### Environment Not Activated

Activate the virtual environment before running the notebook:

#### Windows

```bash
nids_env\Scripts\activate
```

#### Linux/macOS

```bash
source nids_env/bin/activate
```

---

## Deactivate Environment

After completing the project:

```bash
deactivate
```

---

# Project File

```text
Network_Intrusion_Detection_System.ipynb
```

Run all notebook cells using **Shift + Enter** to execute the complete Network Intrusion Detection System project successfully.
