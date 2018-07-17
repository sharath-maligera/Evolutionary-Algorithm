# Evolutionary-Algorithm
Implements a mini-version of an Evolutionary Algorithm.
- The Evolutionary Algorithm shall find the maximum of a function f(g). 
- Implements a mini population of P = 2 individuals, each with a genome g that is a vector of L real values.
- The external selection step keeps only the best one of the two individuals, and discards the other one. 
- The inheritance step is just copying the surviving genome to be the newly created genome. 
- The mutation step is only performed for the newly created genome by just adding a small random vector r to the genome, each of the L components of r shall be normally distributed distributed between −ε
and +ε.
- Fitness evaluation is just calculating the fitness function f(g) for all P genomes of the population, and providing the results for the external selection process.

