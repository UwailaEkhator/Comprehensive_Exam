# Climate Change Opinion Dynamics and Stance Detection


## Overview
This repository contains the computing artifact for my PhD Comprehensive Exam. The focus of the artifact is to compare the performance of In-context learning (ICL) and Finetuning on training data subsets (10%, 20%, 30%, 40%, 50%, 60%, 70%, 80% and 100%) of the [SemEval-2016](https://www.saifmohammad.com/WebPages/StanceDataset.htm) stance dataset. The entire test data set is used to evaluate the Finetuned model and the ICL model.


## How to setup and run this project
1. Clone the repository:
   ```
    git clone https://github.com/UwailaEkhator/Comprehensive_Exam.git
   ```
2. Launch Anaconda and Open Jupyter Notebook or JupyterLab
3. Install required packages
   ```
   pip install transformers datasets evaluate accelerate torch tf-keras
   ```
4. Download the SemEval-2016 stance detection dataset from [here](https://www.saifmohammad.com/WebPages/StanceDataset.htm).
5. Prepare the data, using the code in Computing_Artifact/Data_Preparation.ipynb
6. Finetune the BERTweet model using the code in Computing_Artifact/Finetuning_BERTweet_model.ipynb
7. Run the In-context learning model using the code in Computing_Artifact/Applying_ICL.ipynb
8. Compare the results from both models using the code in Computing_Artifact/Comparing_ICL_and_Finetuning.ipynb



