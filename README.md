# Instructions 

In order to run this assignment, You need to install different python libraries such as matplotlib, collection and numpy

#### To run the code file, 
We need to provide different command line arguments. For example 
python main.py inst_dir alg nRuns nRestarts nFlips wp tl sNum

inst_dir: Program file and location of the dataset.
alg: Algorithm to run (e.g., 'gsat' for GSAT).
nRuns: Number for executing the algorithm.
nRestarts: Number for the restart parameter.
nFlips: Number for the maximum flips allowed.
wp: Probability (float) in place of wp.
tl: Length of the tabu list.
sNum: Student ID.

we need to pass the program file, location of the dataset, the algorithm you want to run such as for GSAT, the alg will be 'gsat' 
after that we need to pass the number for which we want to execute the algorithm and a number for the restart parameter and the number for the maximum flips allowed
and inplace of wp, we need to pass probability probably in the form of float and t1 is the length of the tabu list and at the end, we need to pass the student id 

Here is the example that I use to run the program :

python main.py myfolder/ gsat 10 50 500 0.1 10 241765


## Aditional Stuff
In the code, I have added three additional functions
- def normalize(values)
    This is used to bring the values between the zero and one scale

These two functions are responsible for plotting the graph after the completion of the execution  
- def plot_normalized_metrics(instances, avg_restarts, avg_flips, avg_time)
- def plot_solved_instances_and_avg_objective(instances, solved_instances, avg_objective)
