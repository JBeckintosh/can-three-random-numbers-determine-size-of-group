# I was trying to check a little math problem
## Could someone figure out the size of a group of between (inclusive) 20 and 50 people using three random numbers, with a few caveats:
- Caveat 1: All random numbers must be greater than 1 and less than 16
- Caveat 2: The first random number must be odd
- Caveat 3: The second random number must be even
- Caveat 4: The third random number must not be equal to the first or second random number

## What is the website doing?
#### This simple website creates three arrays of possible sizes of the group using the random numbers and the remainders not in the group when the sub-groups of the main group are made of the size of the random number
- This creates three arrays of possible values that the groups can be
- Then you can filter one of the arrays, checking to see that the other two arrays also contain that number

## Does it work?
Most of the time, but no it doesn't
There are some rare cases where the size of the group could be two or three options

## How to get it to work
You would need to further restrict how small the random numbers can be as the smaller numbers allow for more values in the array of potential values of the group size
For example:
- If caveat 2 instead said "the first random number must be 5
- And if caveat 3 instead said "the second random number must be 8"
