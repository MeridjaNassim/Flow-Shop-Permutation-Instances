# Flow-Shop-Permutation-Instances
A randomly generated set of of flow shop of permutation instances 

# Installation
- `git clone https://github.com/MeridjaNassim/Flow-Shop-Permutation-Instances.git`
- `cd Flow-Shop-Permutation-Instances`
- Copy the json folder content into your project

# Structure
## JSON instances
- **jobs** : number of jobs in the instance
- **machines** : number of machines in the instance 
- **instance** : a 2D array where each row represents a job and each elements (i,j) is the cost of job i on machine j
- **distribution** : the distribution used to generate the costs
- **optimal_seq** : the optimal scheduling sequence found by running the exact method Branch and bound on the instance.
- **makespan** : the finishing date of the last task on the last machine ( the objective function to minimize )

## Tailard instances (TXT)

These are the tailard benchmark instances for the Flow shop sequencing problem .
You can find them and other benchmarks for the Scheduling problem [through this link](http://mistic.heig-vd.ch/taillard/problemes.dir/ordonnancement.dir/ordonnancement.html) 
# Usage 
You need to parse the json into a the corresponding structure of your code before usage
