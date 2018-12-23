# Knot Reduction in Maude

Maude project for the Fundamentals of Reactive Systems course at Unicam.

## Usage
Load the file in maude
```
$ maude Knot.maude
```
Then run the following command to reduce a knot.
```
Maude> search [1] in R-MOVES : G =>+ ~ .
```
Where __G__ is the Gauss Code relative to the knot to be reduced.
Example:
```
Maude> search [1] in R-MOVES : -2 ; -3 ; 1 ; -1 ; -4 ; 4 ; 2 ; 3 =>+ ~ .
```

The output will be something like that
```
search [1] in R-MOVES : -2 ; -3 ; 1 ; -1 ; -4 ; 4 ; 2 ; 3 =>+ ~ .

Solution 1 (state 41519)
states: 41520  rewrites: 12536251 in 0ms cpu (4100ms real) (~ rewrites/second)
empty substitution
```
