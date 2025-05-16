# PreMatch

A prediction-based scheduling method for dataflow processing applications on computing devices.


```BibTex
@inproceedings{10.1145/3672608.3707986,
author = {Mehran, Narges and Najafabadi Samani, Zahra and Afzal, Samira and Prodan, Radu and Pallas, Frank and Dorfinger, Peter},
title = {PreMatch: A Prediction-based Scheduler for Dataflow Asynchronous Processing on the Computing Continuum},
year = {2025},
isbn = {9798400706295},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3672608.3707986},
doi = {10.1145/3672608.3707986},
abstract = {The popularity of asynchronous data exchange patterns has recently increased, as evidenced by 23\% of the communication between microservices in an Alibaba trace analysis. Such workloads necessitate methods for reducing dataflow processing and completion time by forecasting the future requirements of their microservices and (re-)scheduling them. Therefore, we investigate a prediction-based scheduling method of asynchronous dataflow processing applications by considering the stochastic changes due to dynamic user requirements. We present a microservice scaling and scheduling method named PreMatch combining a machine learning (ML) prediction strategy based on gradient boosting with ranking and game theory matching scheduling principles. Firstly, PreMatch predicts the number of microservice replicas, and then, the ranking method orders the microservice replicas and devices based on microservice and transmission times. Thereafter, the PreMatch schedules microservice replicas requiring dataflow processing on computing devices. Experimental analysis of the PreMatch method shows lower completion times on average 13\% compared to a related prediction-based scheduling method.},
booktitle = {Proceedings of the 40th ACM/SIGAPP Symposium on Applied Computing},
pages = {316–324},
numpages = {9},
keywords = {microservice, replication, computing continuum, gradient boosting regression, multilayer perceptron},
location = {Catania International Airport, Catania, Italy},
series = {SAC '25}
}
```
