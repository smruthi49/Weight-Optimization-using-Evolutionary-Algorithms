## Weight Optimization using Evolutionary Algorithms

This repository contains the Whitebox implementation of Ant Colony Optimization, Cultural Algorithm, Genetic Algorithm, and Particle Swarm Optimization for optimizing neural network weights. These algorithms can be used to train neural networks in a more efficient manner, by finding the optimal values for the weights.


### Implemented Algorithms

    Ant Colony Optimization
    Cultural Algorithm
    Genetic Algorithm
    Particle Swarm Optimization

Each algorithm has been implemented in a separate Python file, which contains the necessary functions and parameters for running the algorithm.

### Neural Network Architecture

The neural network used in this repository has the following architecture:

    Input layer: 12 neurons (for 12 features)
    Hidden layer: 10 neurons
    Output layer: 1 neuron
    
## Accuracy Comparison
   
| Algorithm                | Test Accuracy |
|--------------------------|---------------|
| Ant Colony Optimisation | 73.39% |
| Cultural Algorithm       | 68.75%        |
| Genetic Algorithm        | 76.5%         |
| Particle Swarm Optimisation | 88.54% |

## Genetic Algorithm
| Hidden Layer Size | Generations | Chromosomes | Mating Parents | Crossover Rate | Mutation Rate | Train Accuracy | Test Accuracy |
|-------------------|-------------|-------------|----------------|----------------|---------------|----------------|---------------|
| 7                 | 25          | 40          | 10             | 0.80           | 0.4           | 0.7357         | 0.7396        |
| 10                | 25          | 40          | 10             | 0.80           | 0.4           | 0.6745         | 0.6510        |
| 10                | 30          | 40          | 10             | 0.80           | 0.4           | 0.7435         | 0.7448        |
| 10                | 20          | 30          | 10             | 0.85           | 0.3           | 0.8398         | 0.8490        |

## Inference
 Particle Swarm optimisation gave the best results in comparison with the other three evolutionary algorithms
