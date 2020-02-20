# Temporal Difference For Cliff Walking Problem

* I will write my own implementations of many Temporal-Difference (TD) methods. *

In this project, you will design an agent to learn the Cliff Walking Problem and use an instance of the Cliff Walking environment provide by OpenIA. 

## Project Instructions

1. Clone the repository and navigate to the downloaded folder.

```
git clone https://github.com/TemporalDifferenceForCliffWalking.git
cd TemporalDifferenceForCliffWalking
```

2. Create and activate a new environment.

```
conda create -n cliffWalking python=3.6 matplotlib numpy pandas
source activate cliffWalking
```

3. Create an [IPython kernel](http://ipython.readthedocs.io/en/stable/install/kernel_install.html) for the `cliffWalking` environment. 
```
python -m ipykernel install --user --name cliffWalking --display-name "cliffWalking"
```

4. Open the notebook.
```
jupyter notebook Temporal_Difference.ipynb
```

5. Before running code, change the kernel to match the `cliffWalking` environment by using the drop-down menu (**Kernel > Change kernel > quadcop**). Then, follow the instructions in the notebook.

6. You will likely need to install more pip packages to complete this project.  Please curate the list of packages needed to run your project in the `requirements.txt` file in the repository.
