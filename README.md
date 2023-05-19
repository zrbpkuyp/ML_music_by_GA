# ML_music_by_GA
Compose Music with Genetic Algorithm

This is the final assignment of PKU lesson "Music and Math".
The code is written by Runbo Zhang and Penglin Cai.

Following is how music is composed:
1. Given a certain melody as input.
2. Calculate the transition probabilities of the notes.
3. Initialize the population（size = N）randomly with transition probabilities.
4. Calculate the fitnesses and select M best individuals, then use crossover, mutation, inversion, retrograde, transposition and other methods to generate new individuals, and add them to the population. If the population number exceeds the max number we set, then we filter some by their fitnesses.
5. Repeat step 4 until the iteration is over or the max fitness is more than a certain level.
6. Choose the best music!

Our code includes both pitch and duration!

Many parameters still need to be tuned.
