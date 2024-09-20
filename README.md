Cognitive Modelling, 2024
Assignment 1

Perception Decision Making
Authors: Valeria Rezan, Beyza Celep, Matiss Kalnare, Catherine Smeyers

Files Overview
tutorial_1A.ipynb: Model definition, simulation and comparison.

tutorial_1B.ipynb: Parameter recovery and validation.

tutorial_1C.ipynb: Model selection, model recovery and additional analyses.

tutorial_1_lib.py: A helper script that contains functions used across the notebooks.

dataset_tutorial1.csv: A dataset used for the assignment

The notebooks use Python libraries for data analysis, visualization, and statistical modeling.

For a detailed explanation of each notebook, the methods, and expected results, refer to the accompanying PDF report, which provides a complete breakdown of the project. It contains descriptions of the code and analysis as well as interpretations of the results.

--
How to run
--

# PREREQUISITES
To run this project, ensure you have the following installed:

-- Python 3.x
-- Jupyter Notebook (or VSCode with Jupyter extension)

SETTING UP THE ENVIRONMENT
To ensure that all dependencies are properly installed, follow these steps to set up a virtual environment:

# 1. Create and Activate a New Virtual Environment

  USING conda
  Create a new conda environment
  conda create --name <env_name> python=3.x

   Activate the environment
  conda activate <env_name>

  OR USING venv
  
  Create a virtual environment
  python -m venv <env_name>

  Activate the environment
  On Windows
  <env_name>\Scripts\activate

  On macOS/Linux
  source <env_name>/bin/activate

# 2. Install the Required Dependencies

   Once the environment is activated, navigate to the project directory and install the dependencies listed in requirements.txt:

   pip install -r requirements.txt

# 3. Launch the Jupyter Notebooks

  If you're using Jupyter Notebook, launch it by running:

  jupyter notebook

If you're using VSCode, ensure the Jupyter extension is installed. You can open the notebooks directly within VSCode and select the virtual environment created earlier as the interpreter.
