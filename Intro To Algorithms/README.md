# Intro to Algorithms

## Big O
- Order of magnitude of complexity

## Constant Time
- O(1): The runtime of the algorithm is independent of the size of the data set. If n is 1 or 1 million it takes the same amount of time to execute the algorithm.

## Logarithmic Time
- O(log n): The runtime of the algorithm increases logarithmically as the size of the data set increases.

## Linear Time
- O(n): The runtime of the algorithm is directly proportional to the size of the data set.

## Quadratic Time
- O(n^2): The runtime of the algorithm increases by a factor of n squared as the size of the data set increases.

## Quasilinear Time 
- O(n log n): Given a data set of size n, the algorithm executes an n number of operations where each operation runs in log n (logarithmic) time

## Polynomial runtimes 
- O(n ^ k): An algorithm is considered to have a polynomial runtime if, for a given value of n, it's worst case runtime is in the form of n raise to the k power. Examples of this are O(n^2) and O(n^3). Algorithms with polynomial runtimes are considered efficient.

## Exponential runtime 
- O(k^n): A runtime where number of operations increases exponentially as the size of the data set increases. Exponential runtimes are considered inefficient.

## Combinatorial or factorial runtime 
- O(n!) - Runtimes where as the size of n increases the number of operations increases by n! where n! is the factorial of n.