![Polars library logo](assets/PolarsLogo.jpg)

# Data Analysis with Polars and Python

This repo contains the datasets and Jupyter Notebooks for the
**Data Analysis with Polars and Python** course.

## Setup Instructions

1. Install the `uv` command-line program for managing Python projects.
   - Follow the instructions at https://docs.astral.sh/uv/getting-started/installation/.
2. Download or clone this repository locally.

If you have Git installed, execute `git clone git@github.com:paskhaver/data-analysis-with-polars-and-python.git`

If you do not have Git installed, click the green `Code` button, then click `Download ZIP`.

If downloading directly from GitHub, you'll receive a compressed `.zip` file. You'll need to unzip it to access its contents.

- On macOS, double-click the `data-analysis-with-polars-and-python` zip folder to unzip it.
- On Windows, right-click the zipped `data-analysis-with-polars-and-python` folder, select `Extract All...`, and choose your destination folder.

3. Open your command-line application (i.e., Terminal, PowerShell) and navigate to the `data-analysis-wth-polars-and-python` folder.
4. Execute `uv sync`. This command will:
   - Download Python (the base language)
   - Download Polars (the data analysis library)
   - Download Jupyter Lab (the development environment)

The exact version of Python, Polars, and all other libraries can be found in the `pyproject.toml` file.

## Two Folders

The `incomplete` and `complete` folders contain the exact same files.

The Jupyter Notebooks in the `incomplete` folder have empty code cells. Watch along with the videos and practice writing the code inside the Notebook. You'll complete them as you progress through the course. Feel free to experiment!

The `complete` folder contains my _completed_ Jupyter Notebooks from the recording of the
course. I recommend using these as a backup resource if a code sample does not work or if you want to compare our results.

## Startup and Shutdown

1. Execute `uv run jupyter-lab` to launch Jupyter Lab. Jupyter Lab should launch in your
   default web browser (i.e., Chrome). If it doesn't open, navigate to the link `localhost:8888`
   in your browser.
2. In Jupyter Lab, use the left-hand file explorer to navigate into the `incomplete` folder.
3. Open the Jupyter Notebook for your current course section.
4. Locate the section of the Notebook corresponding to the current lesson video. There is a Table of Contents icon on the left-hand side of Jupyter Lab if you'd like to navigate to any of the headings in the Notebook. The lessons appear in the same order as they do in the video course.
5. When you're done learning, save your work (`Cmd + S` on macOS, `Ctrl + S` on Windows, or press `File > Save All`).
6. Close the tabs corresponding to your open Jupyter Notebooks.
7. Click the Stop icon on the left-hand navigation bar (second button from the top).
8. In the **Kernels** section, click `Shut Down All`. Confirm your choice in the modal that appears.
9. Close the browser.
10. In your terminal, shut down your Jupyter Lab server with the shortcut `Ctrl + C`. Close your Terminal.
