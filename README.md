# Decoupling_OA_Omega
Codes for investigating the decoupling of Ocean Acidification (OA) and carbonate saturation state
Author: Shihan Li (shihan@tamu.edu)

## Repository Structure

- **`ph_omega_backend.py`**  
  Core backend file containing all model functions for simulating the carbonate system.  

- **`Experiments.ipynb`**  
  Jupyter Notebook to run baseline and sensitivity experiments.  

- **`Results_analysis.ipynb`**  
  Jupyter Notebook for analyzing and plotting experiment results.  

- **CSV files (`*.csv`)**  
  Output data from model experiments, including baseline and sensitivity tests:  
  - `petm_results.csv` — PETM scenario results  
  - `sens_camg_results.csv` — Ca/Mg sensitivity  
  - `sens_exp_rrain_results.csv` — rain ratio sensitivity  
  - `sens_nsi_results.csv` — climate sensitivity  
  - `sens_nsi_results_20kyr.csv` — extended 20 kyr run  
  - `sens_pcycle_results.csv` — P cycle sensitivity  
  - `sens_rrain_results.csv` — rain ratio experiments  
  - `sens_sclim_results.csv` — climate feedback sensitivity  

## Usage

1. Run **`Experiments.ipynb`** to generate baseline and sensitivity experiment outputs.  
2. Use **`Results_analysis.ipynb`** to process outputs and generate figures.  
3. Model functions are defined in **`ph_omega_backend.py`**.  

