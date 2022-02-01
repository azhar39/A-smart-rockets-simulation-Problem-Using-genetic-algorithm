# A-smart-rockets-simulation-Problem-Using-genetic-algorithm
1. Introduction
2. To show how to utilize a genetic algorithm to determine the best path. A population of rockets
tries to find a path to the target without crashing. The rockets' primary aim is to land in the desired
location without clashing with any impediments. We can see how the rockets change over time
and are able to make their way to their target place in a pretty short length of time. The Genetic
Algorithm (GA) is a search-based optimization tool based on genetics and natural selection
principles. It's commonly used to find optimal or near-optimal solutions to complex problems that
would take an eternity to solve otherwise. It's commonly utilized to tackle optimization issues, as
well as in research and machine learning[1]. In addition, The rockets will automatically learn how
to reach to the target spot. In other words, we produce a generation of rockets that travel randomly
using that genetic process.
2. Methods
Using the selection, mutation, and crossover operators, the genetic algorithm creates new data from
a finite collection of solutions. The output, external, and internal parameters are a quantitative
evaluation of the object's parameters. Figure 1 depicts a broad overview of the genetic algorithm,
which is divided into many phases: generation, crossover, mutation, and selection are all terms
used to describe the process of creating something new To show how to utilize a genetic algorithm to determine the best path. The rockets will
automatically learn how to reach to the target spot. In other words, we produce a generation of
rockets that travel randomly using that genetic process. Following that, we filter the finest ones
and build new ones depending on the bests' motions. A total of 100 rockets will be launched at
random, with the goal of hitting the yellow target. The black rectangular blocks are obstacles that
the rockets must avoid in order to hit the yellow target. This is our effort to study genetic evolution
algorithms, in which the rockets learn from their mistakes and get smarter over time, eventually
hitting the yellow target correctly. As a result, our strategy is built on the idea of genetic algorithms.
In addition, a swarm of rockets tries to make their way to the intended target. Put some barriers in
the way, and the tiny rockets will do their job! Some rockets are on their way to the target; our
mission is to place an impediment in their way and watch them self-evolve and choose their own
course.
3. How does it work
A population of rockets tries to find a path to the target without crashing. We begin with a
population of rockets with DNA that contains random genes. Following the population's life span,
we apply a fitness function to determine the fitness of each rocket. We then choose two rockets as
parents depending on their reproductive potential.
A crossover point in the child's DNA is chosen that includes the first parent's DNA before the
crossover point and the second parent's DNA after the crossover point. We modify some of the
genes in the DNA once a kid is created via crossover. There is an extremely small chance that a
gene may mutate. Mutations are necessary for maintaining population variety and preventing early
convergence. This cycle of selection, crossover, and mutation continues, and after a period of time,
Figure 2:Description of smart Rocketthe population's maximum fitness is reached, beyond which fitness cannot improve. The children
generated are thereafter similar to those of the preceding generation. We may therefore state that
the genetic algorithm has produced a set of solutions to our problem.
Step one: Initialize. Create an N-element population, each with randomly produced DNA.
Step two: Selection. Build a mating pool by assessing the fitness of each member of the population.
Step three: Reproduction. Repeat N times:
I. Based on relative fitness, choose two parents with a high probability.
II. Crossover—by merging the DNA of these two parents, we can produce a "child."
III. Mutation—mutate the child’s DNA based on a given probability.
IV. Add the new child to a new population.
Step four. Return to Step 2 after replacing the old population with the new population.
The rockets' primary aim is to land in the desired location without clashing with any impediments.
We can see how the rockets change over time and are able to make their way to their target place
in a pretty short length of time.
4. DNA
The movement of each Rocket is controlled by its DNA, which is an Array of random 2DVectors.
Prior to determining fitness, mutation happens in such a way that each gene can mutate at a specific
pace.
5. Population
The Population is made up of Rockets with entirely random DNA at start. Define the fitness
function as follows: Given the normalized distance between the target and the Rocket at the end
of its lifespan:
This fitness function predicts the probability of selecting a Rocket as one of the two parents of the
Population's future generation. As a result, the next generation of the Population has a very high
chance of possessing DNA that is extremely similar to that of the previous generation's finest
Rockets.
6. Implementation
The Processing graphics library was used to create this simulation, which was written in
JavaScript.
8. Advantages of Genetic Algorithms
GAs offers a number of advantages that have helped them become quite popular[1]. Among them
are:
1. Does not require any derivative information (which may not be available for many realworld problems).
2. When compared to traditional procedures, it is quicker and more efficient.
3. Has a lot of parallel processing power.
4. Optimizes multi-objective problems as well as continuous and discrete functions.
5. Provides a list of "excellent" solutions rather than just one.
6. Always obtains a problem solution that improves with time.
7. It's beneficial when there are a lot of parameters to examine and the search space is large.
9. Limitations of Genetic Algorithms
Genetic Algorithms, like any other method, has some limits[1]. Among them are:
1. GAs are not applicable in all circumstances, especially those that are simple and for
which derivative data is accessible.
2. The fitness value is computed often, which might be computationally expensive in some
cases.
3. There are no guarantees regarding the solution's optimality or quality because it is
stochastic.
4. If the GA isn't correctly implemented, it may fail to find the best option.
Figure 7:Generation 24 to 32 performance and graph10. Conclusion
To conclude, A population of rockets tries to find a path to the target without crashing. The
movement of each Rocket is controlled by its DNA, which is an Array of random 2DVectors. Prior
to determining fitness, mutation happens in such a way that each gene can mutate at a specific
pace. The rockets' primary aim is to land in the desired location without clashing with any
impediments. We can see how the rockets change over time and are able to make their way to their
target place in a pretty short length of time. The Processing graphics library was used to create this
simulation, which was written in JavaScript. Furthermore, our strategy is built on the idea of
genetic algorithms
