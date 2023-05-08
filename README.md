# TavernDiceCode

This project is a Python simulation of a tabletop dice-rolling game "Stones and Bones" or Tavern Dice, 
which I originally developed as part of a Georgia Tech graduate course ISYE6644 Simulation

Key components:
- Tavern Dice Simulation.ipynb is the main Jupyter notebook for running the simulation
  Blocks of code are useful functions, the final block is the simulation experiment control
  Uncomment the last line to save a CSV file with the metrics from each run
- sbconstants.py file contains key game parameters that are used for simulation; imported as 'sbc' in the Jupyter notebook
- DOE_matrix.csv file; contains subsets of rules to run in a Design of Experiments; referenced by the Jupyter notebook
- TavernGameHist*.csv files are logs of metrics from each DOE run
- TavernDiceSimulation_Analysis.rmd is an R Markdown file which generates charts and analyses from the output of the simulation
