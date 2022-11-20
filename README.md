# Evaluating the behavioural changes of the OpenAI cart pole task solved with a Full Microbial Genetic Algorithm

We optimised a Full Microbial Genetic Algorithm (FMGA) to solve the OpenAI cart pole task: finding a genotype that could keep the pole up for 500 episodes.

Having found a correlation between the number of epochs, the population size, and the fitness of the best individual, we trained an FMGA with 50 individuals over 1000 epochs to get the fittest controller.
<img width="1257" alt="Screenshot 2022-11-20 at 00 55 38" src="https://user-images.githubusercontent.com/56508673/202877667-cc4f37f7-a228-43c2-ac04-738f28490a81.png">

We examined how the position, velocity, angle and rotation rate of the most fit controller at different numbers of epochs change. We found patterns in the failures of controllers, such as an increased velocity before falling. We also found that the fittest controllers keep a consistent pattern in each observed behaviour until the last episodes.
<img width="1247" alt="Screenshot 2022-11-20 at 00 56 06" src="https://user-images.githubusercontent.com/56508673/202877673-0ad2df1e-ff43-4ed7-8578-4e27412613c3.png">
