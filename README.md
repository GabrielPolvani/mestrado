# Mestrado
Python codes used to generate all numerical results presented in my Master's Dissertation.

The "mestrado_codes.zip" file countains three folders:

  - scripts, with all .py files used.
  - data, where all simulated points are saved.
  - results, where the .pdf figures generated are saved.

To reproduce the adopted Python Virtual Environment, follows the steps:

  - Extract archives from "mestrado_codes.zip" in the folder you want to create your Python Virtual Environment.
  - Open the Terminal / Windows Power Shell and type the command line "virtualenv venv"
  - Activate your Virtual Environment with "venv/Scripts/activate"
  - Install all python packages required with the command "pip install -r requirements.txt"
  - Open the venv folder in your Python editor.
  - A single Figure can be simulated by informing the figure number (as it is in the Master's Dissertation) in the script main.py and running it. If you want to generate ALL figures, use the file main2.py. The .npy data will be saved in the data folder and simulation results will be arranged in the results folder, following the folder structure.

## Notes

Some curves plotted by running main.py and main2.py might not be as smooth as those presented in the Master's Dissertation. Fell free to increase the number of Monte Carlo Realizations by changing the variable "num_realizations" in each .py script. Have in mind that some plots takes a lot of time to finish, specially the presented surface plots.

I highly recommend to use AT LEAST num_realizations = 10000.
