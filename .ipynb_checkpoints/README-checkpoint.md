# Name Generator

The code in this file was created following the following tutorials by Andrej Karpathy:
- [The spelled-out intro to language modeling: building makemore](https://youtu.be/PaCmpygFfXo?si=cI9CjTlYbu-LtKKa)
- [Building makemore Part 2: MLP](https://youtu.be/TCH_1BHY58I?si=uR9xtL0Rf0V1gxQM)

The training data used by the various approaches were obtained from the [SSA](https://www.ssa.gov/oact/babynames/). 

This project was created with the objective of generating names using a variety of different methods: currently implementing solutions using
bigram lookup, a basic neural network, and an MLP-based approach. The specifics of each of the respective approaches are detailed below: 

## Bigram

The code for this approach is located in [namegenerator-bigram-neural-network.ipynb](./namegenerator-bigram-neural-network.ipynb). This code
first contains a basic bigram based approach, which stores the frequencies of a given character which follow another provided character from 
a training set. The approach following trains a neural network with one layer, on the provided [names.txt](./names.txt). 

## MLP

This code can be found in [namegenerator-mlp.ipynb](./namegenerator-mlp.ipynb). This follows an approach following [Bengio et al. 2003](https://www.jmlr.org/papers/volume3/bengio03a/bengio03a.pdf). 
