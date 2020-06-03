## Instructions

<b>Dependencies required:</b>
- tensorflow2.x
- keras (comes from tensorflow.keras)
- numpy
- copy
- sklearn
- matplotlib

<b>Setup requirements:</b>
- Set up a folder named 'Images' (same directory as the Jupyter Notebook) to store the output images from the model
- Set up a folder named 'Caches' (same directory as the Jupyter Notebook) to store the caches from the model

<b>Jupyter Notebook Section descriptions:</b>
- <b>Section 1: Generic Initialization</b>
    - Run all the code under Section 1. These are the code to define the main functions required for the experiments
- <b>Section 2: Load Cache to Print Graph (if required)</b>
    - Run the codes here only if you need to print graphs from a cahce in the Caches folder
- <b>Section 3: MNIST</b>
    - Run the codes here for experiments on the MNIST dataset.
        - Section 3.1: Customize Model
            - Allows you to customize the model used for the experiment.
        - Section 3.2: Evaluate Model
            - Allows you to run code to evaluate performance of various metrics.
        - Section 3.3: Oracle Comparison
            - Allows you to run code to evaluate performance of min, max and min_layer metrics against the oracle
        - Section 3.4: Random Initialization
            - Allows you to run code to compare performance of random initialization on the final pruned model vs original initialization
        - Section 3.5: Compare Percent
            - Allows you to run code to compare effect on accuracy based on proportion of nodes/filters dropped per training cycle
- <b>Section 4: CIFAR10</b>
    - Run the codes here for experiments on the CIFAR10 dataset
        - Section 4.1: Customize Model
            - Allows you to customize the model used for the experiment.
        - Section 4.2: Evaluate Model
            - Allows you to run code to evaluate performance of various metrics.
        - Section 4.3: Oracle Comparison
            - Allows you to run code to evaluate performance of min, max and min_layer metrics against the oracle
        - Section 4.4: Random Initialization
            - Allows you to run code to compare performance of random initialization on the final pruned model vs original initialization
        - Section 4.5: Compare Percent
            - Allows you to run code to compare effect on accuracy based on proportion of nodes/filters dropped per training cycle
