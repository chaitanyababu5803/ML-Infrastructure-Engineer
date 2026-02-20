 Distributed Training Strategies
To make this work, researchers use three main types of parallelism: 
Data Parallelism: Splitting the data across GPUs; each has a copy of the model.
Tensor Parallelism: Splitting a single large layer (tensor) across multiple GPUs.
Pipeline Parallelism: Splitting different layers of the model across different GPUs. 
