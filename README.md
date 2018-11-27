# Knot Reduction in Maude

Maude project for the Fundamentals of Reactive Systems course at Unicam.

Examples:
```
red 1 ; 2 ; 3 .
result Gauss: 1 ; 2 ; 3
```

```
red remove 1 from 1 ; 2 ; 3 .
result NeGauss: 2 ; 3
```

```
red positionOf 2 in 1 ; 2 ; 3 .
result NzNat: 1
```

```
red add 2 in 1 to 1 ; 3 ; 4 .
result Gauss: 1 ; 2 ; 3 ; 4
```

```
red move 2 to 0 in 1 ; 2 ; 3 .
result Gauss: 2 ; 1 ; 3
```

```
red length(1 ; 2 ; 3) .
result NzNat: 3
```
