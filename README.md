# Cheapest Flights Finder

## Introduction/Problem Statement

There are `n` cities connected by `m` flights. Each flight starts from city `u` and arrives at `v` with a price `p`. Given all the cities and flights, together with starting city `src` and the destination `dest`, we need to find the `cheapest price` 
from `src` to `dest` with up to `k` stops. If there is no such route then, `No Route Found` message should be returned to users.

## Assumptions

We assume that the flight network map is already stored in our database and we have it as one input parameter to our finder algorithm.

For example:

```
total number of cities = n = 3

# [source, destination, price]

flight_network = [
    ['San Francisco', 'India', 1200.67],
    ['India', 'Singapore', 500.34],
    ['New York', 'HongKong', 700.29],
    ['Bangkok', 'Seoul', 400.88],
                .
                .
                .
                .
                .
                .
                .
                .
                .

]
```

## Example

### Expected Input

```
source = src = San Francisco
destination = dest = India
Number of stops = k = 1
```

### Expected Output

price = $900




