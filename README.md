# SubSearch: Robust Estimation and Outlier Detection for Stochastic Block Models via Subgraph Search

This repo contains all the code and data used to perform the experiments appearing in our paper "SubSearch: Robust Estimation and Outlier Detection for Stochastic Block Models via Subgraph Search".

## Dependencies
All the dependencies are described in the `requirements.txt`. Please use Python >3.10.

## Usage
The cells in the `Code` section of the notebook define the classes necessary for running the experiments. The cells under `Experiments` are exactly the cells that ran the experiments whose results are shown in the paper.

Running an experiment essentially consists on instantiating the configuration objects with the desired parameters, passing them to instantiate an object of the experiment class, then calling the `run()` method. Once `run()` is complete, you can visualize the results using the `visualize()` method or its variants, and save the results using pickle.
