# Generative Data Augmentation for Irony Detection

## Repository Structure

This repository contains the code, data, results, and source files for the Bachelor's thesis titled "Generative Data Augmentation for Irony Detection."
### Folders:

- **code:** Contains all files necessary to perform the conducted experiments.

  - [`create_k_fold_spkit_for_training_data.ipynb`](code/create_k_fold_spkit_for_training_data.ipynb): Code to set up the strategized 5-fold of the training data.
  
  - [`create_aug_data_GPT2.ipynb`](code/create_aug_data_GPT2.ipynb): Code to finetune the GPT2 model.
  
  - [`create_aug_data_GPT3.ipynb`](code/create_aug_data_GPT3.ipynb): Code to finetune the GPT3.5 model.
  
  - [`perform_LAMBADA_experiments.ipynb`](code/perform_LAMBADA_experiments.ipynb): Conducts the LAMBADA experiments as described in the research.
  
  - [`data_analysis.ipynb`](code/data_analysis.ipynb): Provides statistical and visual analysis on the obtained results.

  **Note:** Execute the files cell by cell in the stated order to reproduce the experiments.

- **data:** Contains all the data used to run the experiments.

- **results:** Contains the results of the conducted experiments.

- **src:** Contains images used in the thesis.

## Execution Order

To reproduce the experiments, execute the code files in the `code` folder cell by cell in the following order (Alternativly, because the fine-tuning requires some time and a custom API-key, one can start the execution at 4.):

1. [`create_k_fold_spkit_for_training_data.ipynb`](code/create_k_fold_spkit_for_training_data.ipynb)
2. [`create_aug_data_GPT2.ipynb`](code/create_aug_data_GPT2.ipynb)
3. [`create_aug_data_GPT3.ipynb`](code/create_aug_data_GPT3.ipynb)
4. [`perform_LAMBADA_experiments.ipynb`](code/perform_LAMBADA_experiments.ipynb)
5. [`data_analysis.ipynb`](code/data_analysis.ipynb)
