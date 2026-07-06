# OpenScenarioPlayer
This software is completely free and is a open scenario player where you can directly change the parameter and play the scenario.
# OpenScenarioPlayer

A Python-based desktop GUI application for launching and managing OpenSCENARIO simulations with the **esmini** simulator.

<h2>Dashboard</h2>
Dashboard.png


## Features

- Modern GUI built with CustomTkinter
- Open and run OpenSCENARIO scenario files
- Integration with esmini simulator
- File selection dialogs
- XML scenario parsing
- Data handling with pandas
- Scenario visualization support using Matplotlib
- Browser integration for opening related resources
- Packaged executable splash-screen support (PyInstaller)

## Technologies Used

- Python
- CustomTkinter
- Tkinter
- pandas
- Matplotlib
- XML ElementTree
- esmini OpenSCENARIO simulator

## Prerequisites

- Python 3.9+
- esmini simulator installed locally

## Installation

1. Clone the repository:

```bash
git clone https://github.com/<your-username>/OpenScenarioPlayer.git
cd OpenScenarioPlayer
```

2. Install dependencies:

```bash
pip install customtkinter pandas matplotlib
```

3. Update the esmini path if required.

The application uses a default esmini location:

```text
D:\Softwares\esmini-demo_Windows\esmini-demo\bin\esmini.exe
```

You can modify the path in the source code or through application configuration.

## Usage

Run the application:

```bash
python OpenScenarioPlayer.py
```

Launch the GUI, select an OpenSCENARIO file, and execute it using esmini.

## Project Structure

```text
OpenScenarioPlayer.py     # Main application
esmini_path.txt           # Stored esmini executable path
README.md                 # Project documentation
```

## Configuration

The application stores the esmini executable location in:

```text
esmini_path.txt
```

## Author

**Amal Nambiar**

Version: 1.1  
Updated: May 2026

## License

Add your preferred license (MIT, Apache-2.0, GPL-3.0, etc.) before publishing.
