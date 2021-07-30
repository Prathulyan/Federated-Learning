# Federated-Learning

Federated learning aims to build a joint ML model based on the data located at multiple sites. There are two processes in federated learning: model training and model inference. In the process of model training, information can be exchanged between parties but not the data.​

An idea is to train a model at each location where a data source resides, and then let the sites communicate their respective models in order to reach a consensus for a global model​

In federated learning, a fundamental change in algorithmic design methodology is, instead of transferring data from sites to sites, we transfer model parameters in a secure way, so that other parties cannot “second guess” the content of others’ data.
