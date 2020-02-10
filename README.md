## Part 1
To choose the number of iterations per run of the benchmark, I chose the largest number that allowed the program to finish executing in under 1 minute. This resulted in 4 iterations for the largest number of objects (2^24) and many more iterations for smaller powers of 2. I then ran the program several times using this number of iterations and took the minimum as my final result.

## Part 3
Runtimes (2^11 objects)
float: .0006883us
double: .002753us
int_8t: .001603us
int_16t: .001616us
int_32t: .001882us
int_64t: .002047us

## Part 4
PYTHON: update_locations.py total memory used with 2^20 objects: 
~291.6 MB
C++: update_locations total memory used with 2^20 objects: 
~38.6 MB
