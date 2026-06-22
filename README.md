# aigc-5500-midterm-project

# Setup Instructions
1. Download this notebook from our GitHub repository
2. Use an IDE or platform that can read Python notebooks. Some examples include Jupyter Notebook (through Anaconda), Google Colab (requires internet connection), AWS SageMaker AI (requires AWS account and internet), or an IDE of your choice (e.g., VS Code).
3. We recommend using either local GPU through Cuda/MPS. If that is not available, we recommend leveraging GPU from online platforms such as Google Colab.
4. After opening the notebook in the platform of your choice, make sure to install all necessary dependencies as listed below.
5. Restart the kernel to ensure all dependencies are now applied to the session.

# Dependencies
This notebook requires installing the following dependencies and versions:
PyTorch version:     2.12.0
Torchvision version: 0.27.0
Scikit-Learn version:1.8.0
NumPy version:       2.4.6
Matplotlib version:  3.10.9
Optuna version:      4.9.0

A command has been provided in the first runnable cell of the Notebook. To install all of the dependencies, uncomment the installing command and run the cell.

# Reproducing Results
This notebook is self-enclosed and does not contain content copied over from other runs. Therefore, after completing the initial set-up steps to install the dependencies and restarting the kernel, the notebook is ready. Simply click on "Run All" and the notebook will automatically run all cells. This should complete all necessary steps to reproduce the notebook since we have set a manual seed to ensure the same inital states and reproducible outputs.

# Random Seed
We selected 498 as our manual seed for the notebook. This was applied to the torch manual seeding as well as the random state paramteter to other libraries such as Optuna.

