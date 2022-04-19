# BMTK-Loihi Datasets
This dataset lists the different parameter sets and stimulus sets used in the validation of Loihi implementations of LIF models based on BMTK (Brain Modeling ToolKit) simulations, including :
- LIF model parameters for excitatory and inhibitory neurons based on the data from Allen Brain Atlas (https://www.brain-map.org/).
- External spike-train stimulus data generated using random Poisson process.


## Data
- The parameter set data is in JSON format and is used directly into BMTK. It is converted into a python dictionary for use in Loihi.
- The spike-train data is in CSV format.

## Preparation
This repository uses the tutorials for the Point Neuron Models in the [BMTK](https://github.com/AllenInstitute/bmtk) repository to build the networks and run the simulations in BMTK.

For simulations run on Loihi, access to the Loihi software development kit (NxSDK) and the Loihi hardware is needed.
More information can be found in: https://www.intel.com/content/www/us/en/research/neuromorphic-community.html For community support, Q&A and other information, please visit: http://neuromorphic.intel.com

